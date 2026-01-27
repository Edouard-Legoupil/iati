# codeBudgetIdentifier

IATI Functional and Administrative Common Code : One of several possible
Budget Identifier Vocabularies. As of version 2.03 this codelist has
been deprecated. This is a Non-Core codelist.

## Usage

``` r
codeBudgetIdentifier
```

## Format

A data frame with 152 rows and 6 variables:

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
knitr::kable(head(codeBudgetIdentifier, 10))
}
#> 
#> 
#> |code  |name                                      |description | category|url |status |
#> |:-----|:-----------------------------------------|:-----------|--------:|:---|:------|
#> |1.1.1 |Executive - executive                     |NA          |      1.1|NA  |active |
#> |1.2.1 |Legislative - legislative                 |NA          |      1.2|NA  |active |
#> |1.3.1 |Accountability - macroeconomic policy     |NA          |      1.3|NA  |active |
#> |1.3.2 |Accountability - budgeting                |NA          |      1.3|NA  |active |
#> |1.3.3 |Accountability - planning                 |NA          |      1.3|NA  |active |
#> |1.3.4 |Accountability - Treasury/Accounts        |NA          |      1.3|NA  |active |
#> |1.3.5 |Accountability - debt and aid management  |NA          |      1.3|NA  |active |
#> |1.3.6 |Accountability - tax policy               |NA          |      1.3|NA  |active |
#> |1.3.7 |Accountability - tax collection           |NA          |      1.3|NA  |active |
#> |1.3.8 |Accountability - local government finance |NA          |      1.3|NA  |active |
```
