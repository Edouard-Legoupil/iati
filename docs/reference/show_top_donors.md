# show_top_donors

Who are the main donors by country in terms of transaction?

## Usage

``` r
show_top_donors(
  year,
  programme_lab = NULL,
  iati_identifier_ops = NULL,
  ctr_name = NULL,
  top_n = 5
)
```

## Arguments

- year:

  year to select starting from 2016 - could be one year or a list

- programme_lab:

  A character vector corresponding to the name of the programme.

- iati_identifier_ops:

  A character vector corresponding to the name of the operation.

- ctr_name:

  A character vector corresponding to the name of the country.

- top_n:

  top n donors to show - the rest being lumped together

## Value

a graph

## Examples

``` r
show_top_donors(year = 2025,
           ctr_name = "Brazil", 
           top_n = 5)

show_top_donors(year = 2022,
           ctr_name = "Brazil", 
           top_n = 10)
```
