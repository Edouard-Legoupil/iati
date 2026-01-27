# codeIndicatorMeasure

To specify how an indicator is being measured. This includes qualitative
and quantitative values.

## Usage

``` r
codeIndicatorMeasure
```

## Format

A data frame with 5 rows and 6 variables:

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
knitr::kable(head(codeIndicatorMeasure, 10))
}
#> 
#> 
#> | code|name        |description                                                |category |url |status |
#> |----:|:-----------|:----------------------------------------------------------|:--------|:---|:------|
#> |    1|Unit        |The indicator is measured in units.                        |NA       |NA  |active |
#> |    2|Percentage  |The indicator is measured in percentages                   |NA       |NA  |active |
#> |    3|Nominal     |The indicator is measured as a quantitative nominal scale. |NA       |NA  |active |
#> |    4|Ordinal     |The indicator is measured as a quantitative ordinal scale. |NA       |NA  |active |
#> |    5|Qualitative |The indicator is qualitative.                              |NA       |NA  |active |
```
