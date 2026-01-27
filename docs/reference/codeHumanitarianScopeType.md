# codeHumanitarianScopeType

The Humanitarian Scope Type codelist defines codes for types of
humanitarian events and actions.

## Usage

``` r
codeHumanitarianScopeType
```

## Format

A data frame with 2 rows and 6 variables:

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
knitr::kable(head(codeHumanitarianScopeType, 10))
}
#> 
#> 
#> | code|name      |description |category |url |status |
#> |----:|:---------|:-----------|:--------|:---|:------|
#> |    1|Emergency |NA          |NA       |NA  |active |
#> |    2|Appeal    |NA          |NA       |NA  |active |
```
