# Show a treemap of top funding partners

This function creates a treemap to visualize the top N funding partners
based on their total incoming commitments for a given year and location.

## Usage

``` r
show_funding_partners_treemap(
  year,
  ctr_name = NULL,
  programme_lab = NULL,
  iati_identifier_ops = NULL,
  top_n = 10
)
```

## Arguments

- year:

  A numeric value for the year.

- ctr_name:

  A character vector for the country name.

- programme_lab:

  A character vector for the programme name.

- iati_identifier_ops:

  A character vector for the operation ID.

- top_n:

  The number of top donors to display. Others will be aggregated into an
  "Other" category.

## Examples

``` r
show_funding_partners_treemap(year = 2025, ctr_name = "Brazil", top_n = 10)
```
