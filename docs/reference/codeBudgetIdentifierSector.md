# codeBudgetIdentifierSector

This codelists exists to group the Budget Identifier codelist into
sectors. It is not used as a codelist in its own right. This is a
Non-Core codelist.

## Usage

``` r
codeBudgetIdentifierSector
```

## Format

A data frame with 31 rows and 6 variables:

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
knitr::kable(head(codeBudgetIdentifierSector, 10))
}
#> 
#> 
#> | code|name                       |description | category|url |status |
#> |----:|:--------------------------|:-----------|--------:|:---|:------|
#> |  1.1|Executive                  |NA          |        1|NA  |active |
#> |  1.2|Legislative                |NA          |        1|NA  |active |
#> |  1.3|Accountability             |NA          |        1|NA  |active |
#> |  1.4|External Affairs           |NA          |        1|NA  |active |
#> |  1.5|General Personnel Services |NA          |        1|NA  |active |
#> |  1.6|Statistics                 |NA          |        1|NA  |active |
#> |  1.7|Other General Services     |NA          |        1|NA  |active |
#> |  1.8|Elections                  |NA          |        1|NA  |active |
#> |  2.1|Justice, Law and Order     |NA          |        2|NA  |active |
#> |  2.2|Defence                    |NA          |        2|NA  |active |
```
