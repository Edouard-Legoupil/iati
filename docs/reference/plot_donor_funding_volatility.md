# Plot donor funding volatility

This function creates a bar chart showing the year-on-year percentage
change in funding for a specific donor.

## Usage

``` r
plot_donor_funding_volatility(
  donor_name,
  programme_lab = NULL,
  iati_identifier_ops = NULL,
  ctr_name = NULL
)
```

## Arguments

- donor_name:

  The name of the donor to plot.

- programme_lab:

  A character vector corresponding to the name of the programme.

- iati_identifier_ops:

  A character vector corresponding to the name of the operation.

- ctr_name:

  A character vector corresponding to the name of the country.
