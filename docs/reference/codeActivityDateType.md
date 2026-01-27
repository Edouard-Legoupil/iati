# codeActivityDateType

Types of date for activities. There are many different business models
and dates that can be used to describe the start and end of activities.
It is recommended that each publisher adopts their own consistent
approach that provides users with a meaningful indication of the
lifespan of an activity.

## Usage

``` r
codeActivityDateType
```

## Format

A data frame with 4 rows and 6 variables:

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
knitr::kable(head(codeActivityDateType, 10))
}
#> 
#> 
#> | code|name          |description                                                                                                                                    |category |url |status |
#> |----:|:-------------|:----------------------------------------------------------------------------------------------------------------------------------------------|:--------|:---|:------|
#> |    1|Planned start |The date on which the activity is planned to start, for example the date of the first planned disbursement or when physical activity starts.   |NA       |NA  |active |
#> |    2|Actual start  |The actual date the activity starts, for example the date of the first disbursement or when physical activity starts.                          |NA       |NA  |active |
#> |    3|Planned End   |The date on which the activity is planned to end, for example the date of the last planned disbursement or when physical activity is complete. |NA       |NA  |active |
#> |    4|Actual end    |The actual date the activity ends, for example the date of the last disbursement or when physical activity is complete.                        |NA       |NA  |active |
```
