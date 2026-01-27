# Plot donor geographic diversification over time

Plot donor geographic diversification over time

## Usage

``` r
show_donor_geographic_diversification(
  donor_name,
  start_year = NULL,
  end_year = NULL,
  other_stat = c("mean", "median"),
  verbose = TRUE
)
```

## Arguments

- donor_name:

  The name of the donor to highlight.

- start_year:

  Optional start year filter.

- end_year:

  Optional end year filter.

- other_stat:

  Statistic for "Other donors": one of "mean" or "median".

- verbose:

  Logical, whether to print debug messages.

## Value

A ggplot object.

## Examples

``` r
# Example usage:
p_geo_div <- show_donor_geographic_diversification( 
  donor_name = "Private donors", 
   start_year = 2022, 
   end_year = 2025,
  other_stat = "mean"
  )
print(p_geo_div)

```
