# Plot donor earmarking flexibility over time

This function creates a stacked bar chart showing the proportion of each
earmarking category for a specific donor over several years.

## Usage

``` r
show_donor_earmarking_flexibility_over_time(
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

## Examples

``` r
# Earmarking Flexibility Over Time
show_donor_earmarking_flexibility_over_time(donor_name = "Private donors",
                                            ctr_name = "Syria")


```
