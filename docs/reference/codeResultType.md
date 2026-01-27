# codeResultType

This is a Non-Core codelist.

## Usage

``` r
codeResultType
```

## Format

A data frame with 4 rows and 6 variables:

- `code`:

  double COLUMN_DESCRIPTION

- `name`:

  character COLUMN_DESCRIPTION

- `description`:

  character COLUMN_DESCRIPTION

- `category`:

  logical COLUMN_DESCRIPTION

- `url`:

  logical COLUMN_DESCRIPTION

- `status`:

  character COLUMN_DESCRIPTION

## Source

<https://iatistandard.org/en/iati-standard/203/codelists/resulttype/>

## Examples

``` r
{
knitr::kable(head(codeResultType, 10))
}
#> 
#> 
#> | code|name    |description                                                                                                                                                                 |category |url |status |
#> |----:|:-------|:---------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:--------|:---|:------|
#> |    1|Output  |Results of the activity that came about as a direct effect of your work and specific, what is done, and what communities are reached. For example, X number of individuals. |NA       |NA  |active |
#> |    2|Outcome |Results of the activity that produce an effect on the overall communities or issues you serve. For example lower rate of infection after a vaccination programme.           |NA       |NA  |active |
#> |    3|Impact  |The long term effects of the outcomes, that lead to larger, over arching results, such as improved life-expectancy.                                                         |NA       |NA  |active |
#> |    9|Other   |Another type of result, not specified above.                                                                                                                                |NA       |NA  |active |
```
