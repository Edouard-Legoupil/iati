# show_budget_gap

UNHCR budgets are needs-based: it represents the total amount of money
that would be required were UNHCR to meet all of the needs that it is
seeking to address.

## Usage

``` r
show_budget_gap(
  year,
  programme_lab = NULL,
  iati_identifier_ops = NULL,
  ctr_name = NULL,
  weight_by = NULL
)
```

## Arguments

- year:

  A numeric value or a vector of numeric value to filter on year. Note
  that data pre-2022 are using a different set of indicators

- programme_lab:

  A character vector corresponding to the name of the programme.

- iati_identifier_ops:

  A character vector corresponding to the name of the operation.

- ctr_name:

  A character vector corresponding to the name of the country.

- weight_by:

  list of population group to weight the budget - "refugees",
  "asylum_seekers", "returned_refugees" "idps", "returned_idps",
  "stateless", "ooc", "oip" default is null.

## Value

a graph

## Examples

``` r
show_budget_gap(year = c(2022, 2023, 20024, 2025), 
             ctr_name = "Brazil")

show_budget_gap(year = c(2022, 2023, 20024, 2025), 
             ctr_name = "Brazil",
             weight_by = c("refugees", "oip"))
#> Warning: There was 1 warning in `dplyr::filter()`.
#> ℹ In argument: `year >= thisyear & coa_name == thisctr_name`.
#> Caused by warning in `year >= thisyear`:
#> ! longer object length is not a multiple of shorter object length
#> Error in dplyr::left_join(df2, dplyr::select(ctrstat, year, weight), by = c("year")): Can't join `x$year` with `y$year` due to incompatible types.
#> ℹ `x$year` is a <double>.
#> ℹ `y$year` is a <factor<2e4a0>>.
```
