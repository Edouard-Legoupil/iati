# codeActivityScope

Geographic scope of activity

## Usage

``` r
codeActivityScope
```

## Format

A data frame with 8 rows and 6 variables:

- `code`:

  double code

- `name`:

  character name

- `description`:

  character description

- `category`:

  double category

- `url`:

  character url

- `status`:

  character status

## Source

<https://iatistandard.org/en/iati-standard/203/codelists/>

## Examples

``` r
{
knitr::kable(head(codeActivityScope, 10))
}
#> 
#> 
#> | code|name                                                  |description                                                                                                             |category |url |status |
#> |----:|:-----------------------------------------------------|:-----------------------------------------------------------------------------------------------------------------------|:--------|:---|:------|
#> |    1|Global                                                |The activity scope is global                                                                                            |NA       |NA  |active |
#> |    2|Regional                                              |The activity scope is a supranational region                                                                            |NA       |NA  |active |
#> |    3|Multi-national                                        |The activity scope covers multiple countries, that don't constitute a region                                            |NA       |NA  |active |
#> |    4|National                                              |The activity scope covers one country                                                                                   |NA       |NA  |active |
#> |    5|Sub-national: Multi-first-level administrative areas  |The activity scope covers more than one first-level subnational administrative areas (e.g. counties, provinces, states) |NA       |NA  |active |
#> |    6|Sub-national: Single first-level administrative area  |The activity scope covers one first-level subnational administrative area (e.g. country, province, state)               |NA       |NA  |active |
#> |    7|Sub-national: Single second-level administrative area |The activity scope covers one second-level subnational administrative area (e.g. municipality or district)              |NA       |NA  |active |
#> |    8|Single location                                       |The activity scope covers one single location (e.g. town, village, farm)                                                |NA       |NA  |active |
```
