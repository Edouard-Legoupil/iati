# codeCollaborationType

OECD DAC classification used to determine the character of resource
flows (bilateral or multilateral). External URL:
http://www.oecd.org/dac/stats/dacandcrscodelists.htm

## Usage

``` r
codeCollaborationType
```

## Format

A data frame with 7 rows and 6 variables:

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

<https://iatistandard.org/en/iati-standard/203/codelists/collaborationtype/>

## Examples

``` r
{
knitr::kable(head(codeCollaborationType, 10))
}
#> 
#> 
#> | code|name                                                                               |description                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |category |url |status |
#> |----:|:----------------------------------------------------------------------------------|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:--------|:---|:------|
#> |    1|Bilateral                                                                          |NA                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |NA       |NA  |active |
#> |    2|Multilateral (inflows)                                                             |NA                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |NA       |NA  |active |
#> |    3|Bilateral, core contributions to NGOs and other private bodies / PPPs              |NA                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |NA       |NA  |active |
#> |    4|Multilateral outflows                                                              |NA                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |NA       |NA  |active |
#> |    6|Private Sector Outflows                                                            |NA                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |NA       |NA  |active |
#> |    7|Bilateral, ex-post reporting on NGOs’ activities funded through core contributions |NA                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |NA       |NA  |active |
#> |    8|Bilateral, triangular co-operation.                                                |Activities where one or more bilateral providers of development co-operation or international organisations support South-South co-operation, joining forces with developing countries to facilitate a sharing of knowledge and experience among all partners involved. (Activities that only involve bilateral providers or multilateral agencies without a South-South co-operation element (e.g. joint programming, pooled funding or delegated co-operation) should not be assigned bi_multi 8.) |NA       |NA  |active |
```
