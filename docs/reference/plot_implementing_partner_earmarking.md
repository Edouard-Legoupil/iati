# Plot implementing partner earmarking

This function plots the earmarking of funding for a specific
implementing partner.

## Usage

``` r
plot_implementing_partner_earmarking(
  partner_name,
  year = NULL,
  by = "global",
  programme_lab = NULL,
  iati_identifier_ops = NULL,
  ctr_name = NULL
)
```

## Arguments

- partner_name:

  The name of the implementing partner to plot.

- year:

  A numeric value or a vector of numeric values to filter on year.

- by:

  The category to group by. One of "date", "global", "region",
  "country", "sector".

- programme_lab:

  A character vector corresponding to the name of the programme.

- iati_identifier_ops:

  A character vector corresponding to the name of the operation.

- ctr_name:

  A character vector corresponding to the name of the country.
