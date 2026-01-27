# Plot donor funding over time

This function plots the funding from a specific donor over time, with
options to group the data by different categories.

## Usage

``` r
plot_donor_funding_over_time(
  donor_name,
  year = NULL,
  by = "global",
  programme_lab = NULL,
  iati_identifier_ops = NULL,
  ctr_name = NULL,
  top_n_countries = 10
)
```

## Arguments

- donor_name:

  The name of the donor to plot.

- year:

  A numeric value or a vector of numeric values to filter on year.

- by:

  The category to group by. One of "global", "region", "country",
  "sector".

- programme_lab:

  A character vector corresponding to the name of the programme.

- iati_identifier_ops:

  A character vector corresponding to the name of the operation.

- ctr_name:

  A character vector corresponding to the name of the country.

- top_n_countries:

  The number of top countries to show when \`by = "country"\`.
