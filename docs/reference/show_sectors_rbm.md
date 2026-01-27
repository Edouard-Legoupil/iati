# show_sectors_rbm

What are the most funded sectors per country based on new RBM framework

## Usage

``` r
show_sectors_rbm(
  year,
  programme_lab = NULL,
  iati_identifier_ops = NULL,
  ctr_name = NULL
)
```

## Arguments

- year:

  A numeric value or a list of value.

- programme_lab:

  A character vector corresponding to the name of the programme.

- iati_identifier_ops:

  A character vector corresponding to the name of the operation.

- ctr_name:

  A character vector corresponding to the name of the country.

## Value

a graph

## Examples

``` r
show_sectors_rbm( year =  c(2017, 2018, 2019, 2020, 2021, 2022), 
             ctr_name = "Brazil")
#> Error in dplyr::left_join(df, df_bud2, by = c("year")): Can't join `x$year` with `y$year` due to incompatible types.
#> ℹ `x$year` is a <factor<68191>>.
#> ℹ `y$year` is a <double>.
```
