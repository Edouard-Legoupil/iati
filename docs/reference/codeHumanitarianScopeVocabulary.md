# codeHumanitarianScopeVocabulary

The Humanitarian Scope Vocabulary codelist defines a range of external
codelists which themselves provide codes and descriptions for
humanitarian events and actions.

## Usage

``` r
codeHumanitarianScopeVocabulary
```

## Format

A data frame with 3 rows and 6 variables:

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
knitr::kable(head(codeHumanitarianScopeVocabulary, 10))
}
#> 
#> 
#> |code |name                   |description |category |url                                                   |status |
#> |:----|:----------------------|:-----------|:--------|:-----------------------------------------------------|:------|
#> |1-2  |Glide                  |NA          |NA       |http://glidenumber.net/glide/public/search/search.jsp |active |
#> |2-1  |Humanitarian Plan      |NA          |NA       |https://fts.unocha.org/plan-code-list-iati            |active |
#> |99   |Reporting Organisation |NA          |NA       |NA                                                    |active |
```
