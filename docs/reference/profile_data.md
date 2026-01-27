# Profile Plot Data

This function generates a statistical profile of the data used in the
plot to provide context for the AI.

## Usage

``` r
profile_data(p)
```

## Arguments

- p:

  A \`ggplot\` object.

## Value

A list containing:

- distributions:

  A \`skim_df\` object summarizing mapped variables.

- correlations:

  A list of correlation coefficients (if applicable).

## Details

It performs two main tasks: 1. \*\*Distribution Analysis\*\*: Uses
\`skimr::skim()\` to summarize variables mapped in the plot. 2.
\*\*Correlation Check\*\*: For scatterplots (\`geom_point\`), it
calculates Pearson correlations to help the AI identify relationships.

## Examples

``` r
library(ggplot2)
p <- ggplot(mtcars, aes(x = wt, y = mpg)) +
  geom_point() +
  unhcrthemes::theme_unhcr(grid = "Y", axis = "X", axis_title = FALSE) +
  labs(
    title = "Vehicle Efficiency",
    subtitle = "Fuel consumption vs weight",
    caption = "Source: mtcars dataset"
  )

profile_data(p)
#> $distributions
#> ── Data Summary ────────────────────────
#>                            Values   
#> Name                       df_mapped
#> Number of rows             32       
#> Number of columns          2        
#> _______________________             
#> Column type frequency:              
#>   numeric                  2        
#> ________________________            
#> Group variables            None     
#> 
#> ── Variable type: numeric ──────────────────────────────────────────────────────
#>   skim_variable n_missing complete_rate  mean    sd    p0   p25   p50   p75
#> 1 wt                    0             1  3.22 0.978  1.51  2.58  3.32  3.61
#> 2 mpg                   0             1 20.1  6.03  10.4  15.4  19.2  22.8 
#>    p100 hist 
#> 1  5.42 ▃▃▇▁▂
#> 2 33.9  ▃▇▅▁▂
#> 
#> $correlations
#> $correlations$`wt vs mpg`
#> [1] -0.8676594
#> 
#> 
```
