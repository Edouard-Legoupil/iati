# codeActivityStatus

Lifecycle status of the activity from pipeline to completion

## Usage

``` r
codeActivityStatus
```

## Format

A data frame with 6 rows and 6 variables:

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
knitr::kable(head(codeActivityStatus, 10))
}
#> 
#> 
#> | code|name                    |description                                                                                                                            |category |url |status |
#> |----:|:-----------------------|:--------------------------------------------------------------------------------------------------------------------------------------|:--------|:---|:------|
#> |    1|Pipeline/identification |The activity is being scoped or planned                                                                                                |NA       |NA  |active |
#> |    2|Implementation          |The activity is currently being implemented                                                                                            |NA       |NA  |active |
#> |    3|Finalisation            |Physical activity is complete or the final disbursement has been made, but the activity remains open pending financial sign off or M&E |NA       |NA  |active |
#> |    4|Closed                  |Physical activity is complete or the final disbursement has been made.                                                                 |NA       |NA  |active |
#> |    5|Cancelled               |The activity has been cancelled                                                                                                        |NA       |NA  |active |
#> |    6|Suspended               |The activity has been temporarily suspended                                                                                            |NA       |NA  |active |
```
