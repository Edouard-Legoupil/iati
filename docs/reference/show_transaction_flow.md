# show_transaction_flow

Flow diagramme of transations

## Usage

``` r
show_transaction_flow(
  year,
  programme_lab = NULL,
  iati_identifier_ops = NULL,
  ctr_name = NULL,
  top_n = 10
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

- top_n:

  top n donors to show - the rest being lumped together default is 10

## Value

a graph

## Examples

``` r
show_transaction_flow(year = c(2022, 2023, 20024, 2025), 
                   ctr_name = "Brazil")
#> Warning: The `size` argument of `element_rect()` is deprecated as of ggplot2 3.4.0.
#> ℹ Please use the `linewidth` argument instead.
#> ℹ The deprecated feature was likely used in the ggsankey package.
#>   Please report the issue at <https://github.com/davidsjoberg/ggsankey/issues>.


show_transaction_flow(year = 2023, 
                   ctr_name = "Brazil")
```
