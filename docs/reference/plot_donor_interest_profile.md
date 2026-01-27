# Plot donor interest profile

This function creates a bar chart showing the breakdown of a donor's
funding by sector or region.

## Usage

``` r
plot_donor_interest_profile(
  donor_name,
  by = "sector",
  year = NULL,
  programme_lab = NULL,
  iati_identifier_ops = NULL,
  ctr_name = NULL,
  top_n = 10
)
```

## Arguments

- donor_name:

  The name of the donor to plot.

- by:

  The category to group by. One of "sector" or "region".

- year:

  A numeric value or a vector of numeric values to filter on year.

- programme_lab:

  A character vector corresponding to the name of the programme.

- iati_identifier_ops:

  A character vector corresponding to the name of the operation.

- ctr_name:

  A character vector corresponding to the name of the country.

- top_n:

  The number of top categories to show.
