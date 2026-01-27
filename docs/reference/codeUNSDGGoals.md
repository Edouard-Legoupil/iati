# codeUNSDGGoals

A value from the top-level list of UN sustainable development goals
(SDGs) (e.g. ‘1’) External URL:
https://sustainabledevelopment.un.org/?menu=1300

## Usage

``` r
codeUNSDGGoals
```

## Format

A data frame with 17 rows and 6 variables:

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
knitr::kable(head(codeUNSDGGoals, 10))
}
#> 
#> 
#> | code|name                                                                                                                         |description |category |url |status |
#> |----:|:----------------------------------------------------------------------------------------------------------------------------|:-----------|:--------|:---|:------|
#> |    1|Goal 1. End poverty in all its forms everywhere                                                                              |NA          |NA       |NA  |active |
#> |    2|Goal 2. End hunger, achieve food security and improved nutrition and promote sustainable agriculture                         |NA          |NA       |NA  |active |
#> |    3|Goal 3. Ensure healthy lives and promote well-being for all at all ages                                                      |NA          |NA       |NA  |active |
#> |    4|Goal 4. Ensure inclusive and equitable quality education and promote lifelong learning opportunities for all                 |NA          |NA       |NA  |active |
#> |    5|Goal 5. Achieve gender equality and empower all women and girls                                                              |NA          |NA       |NA  |active |
#> |    6|Goal 6. Ensure availability and sustainable management of water and sanitation for all                                       |NA          |NA       |NA  |active |
#> |    7|Goal 7. Ensure access to affordable, reliable, sustainable and modern energy for all                                         |NA          |NA       |NA  |active |
#> |    8|Goal 8. Promote sustained, inclusive and sustainable economic growth, full and productive employment and decent work for all |NA          |NA       |NA  |active |
#> |    9|Goal 9. Build resilient infrastructure, promote inclusive and sustainable industrialization and foster innovation            |NA          |NA       |NA  |active |
#> |   10|Goal 10. Reduce inequality within and among countries                                                                        |NA          |NA       |NA  |active |
```
