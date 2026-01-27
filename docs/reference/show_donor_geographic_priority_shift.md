# Plot donor geographic priority shift over time (alluvial, CVD-safe colors + correct labels)

Plot donor geographic priority shift over time (alluvial, CVD-safe
colors + correct labels)

## Usage

``` r
show_donor_geographic_priority_shift(
  donor_name,
  top_n_countries = 5,
  start_year = NULL,
  end_year = NULL,
  verbose = TRUE
)
```

## Arguments

- donor_name:

  The donor to highlight.

- top_n_countries:

  Number of top recipient countries to display.

- start_year:

  Optional start year.

- end_year:

  Optional end year.

- verbose:

  Print diagnostic messages.

## Value

A fully labeled ggalluvial plot.

## Examples

``` r
# Example usage: 
show_donor_geographic_priority_shift(
   donor_name = "Private donors", 
   top_n_countries = 7,
   start_year = 2022,
   end_year = 2025
 )
```
