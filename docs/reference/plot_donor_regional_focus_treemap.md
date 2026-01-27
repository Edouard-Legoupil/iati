# Plot donor regional and programme focus as a treemap

This function generates a treemap visualization showing a donor's
funding allocation across UNHCR regions and within those regions, by
programme. The size of each treemap tile can represent either the
absolute funding amount or the share of the donor's total funding for
that programme within a region.

## Usage

``` r
plot_donor_regional_focus_treemap(donor_name, year = NULL, label_font_size = 4)
```

## Arguments

- donor_name:

  Character. The name of the donor to analyze.

- year:

  Numeric or integer vector. Year(s) to filter the data.

- label_font_size:

  Numeric. Base font size for treemap labels.

- measure_type:

  Character. One of "total_amount_usd" (default) or "share". -
  "total_amount_usd": Tile size represents the absolute USD amount. -
  "share": Tile size represents the share of the donor's total funding
  that goes to a specific programme within a specific UNHCR region.

## Value

A ggplot object representing the treemap.

## Examples

``` r
# Example usage:
plot_donor_regional_focus_treemap(
  donor_name = "Private donors",
  year = c(2023, 2024, 2025),
  label_font_size = 3
)
#> Warning: Number of colors (n) in the pal_unhcr palette should be between 1 and 8 


plot_donor_regional_focus_treemap(
  donor_name = "Private donors",
  year = 2025,
  label_font_size = 5
)
#> Warning: Number of colors (n) in the pal_unhcr palette should be between 1 and 8 
```
