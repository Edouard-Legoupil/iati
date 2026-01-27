# Extract Plot Structure and Metadata

This function extracts visual metadata from a ggplot object by forcing a
render build. Unlike simple label extraction, this captures the
"trained" ranges and legend mappings that are actually displayed to the
user.

## Usage

``` r
extract_structure(p)
```

## Arguments

- p:

  A \`ggplot\` object.

## Value

A list containing:

- labels:

  Title, subtitle, caption, and axis labels.

- ranges:

  Exact x and y ranges for each panel (trained).

- guides:

  Mapping of visuals (color/shape) to data values.

- geoms:

  List of geometric layers used.

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

extract_structure(p)
#> $labels
#> <ggplot2::labels> List of 3
#>  $ title   : chr "Vehicle Efficiency"
#>  $ subtitle: chr "Fuel consumption vs weight"
#>  $ caption : chr "Source: mtcars dataset"
#> 
#> $ranges
#> $ranges[[1]]
#> $ranges[[1]]$x_range
#> [1] 1.31745 5.61955
#> 
#> $ranges[[1]]$y_range
#> [1]  9.225 35.075
#> 
#> 
#> 
#> $guides
#> NULL
#> 
#> $geoms
#>  geom_point 
#> "GeomPoint" 
#> 
#> $scales
#> list()
#> 
```
