# Show donor earmarking profiles

This function creates a stacked bar chart to show the earmarking profile
of the top N donors.

## Usage

``` r
show_donor_earmarking_profile(
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

  The number of top donors to display.

## Examples

``` r
show_donor_earmarking_profile(year = 2025, ctr_name = "Brazil", top_n = 10)
```
