# codeOrganisationType

This is a Non-Core codelist

## Usage

``` r
codeOrganisationType
```

## Format

A data frame with 16 rows and 6 variables:

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

<https://iatistandard.org/en/iati-standard/203/codelists/organisationtype/>

## Examples

``` r
{
knitr::kable(head(codeOrganisationType, 10))
}
#> 
#> 
#> | code|name                       |description                                                                            |category |url |status |
#> |----:|:--------------------------|:--------------------------------------------------------------------------------------|:--------|:---|:------|
#> |   10|Government                 |NA                                                                                     |NA       |NA  |active |
#> |   11|Local Government           |Any local (sub national) government organisation in either donor or recipient country. |NA       |NA  |active |
#> |   15|Other Public Sector        |NA                                                                                     |NA       |NA  |active |
#> |   21|International NGO          |NA                                                                                     |NA       |NA  |active |
#> |   22|National NGO               |NA                                                                                     |NA       |NA  |active |
#> |   23|Regional NGO               |NA                                                                                     |NA       |NA  |active |
#> |   24|Partner Country based NGO  |Local and National NGO / CSO based in aid/assistance recipient country                 |NA       |NA  |active |
#> |   30|Public Private Partnership |NA                                                                                     |NA       |NA  |active |
#> |   40|Multilateral               |NA                                                                                     |NA       |NA  |active |
#> |   60|Foundation                 |NA                                                                                     |NA       |NA  |active |
```
