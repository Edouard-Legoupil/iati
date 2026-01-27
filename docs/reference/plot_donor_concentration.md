# Plot donor funding concentration

This function creates a bar chart to visualize donor funding
concentration by showing the percentage of total funding from the top N
donors.

## Usage

``` r
plot_donor_concentration(
  year = NULL,
  programme_lab = NULL,
  iati_identifier_ops = NULL,
  ctr_name = NULL,
  top_n = 10
)
```

## Arguments

- year:

  A numeric value or a vector of numeric values to filter on year.

- programme_lab:

  A character vector corresponding to the name of the programme.

- iati_identifier_ops:

  A character vector corresponding to the name of the operation.

- ctr_name:

  A character vector corresponding to the name of the country.

- top_n:

  The number of top donors to show.
