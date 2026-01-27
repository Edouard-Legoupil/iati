# codeDescriptionType

Activity decription types. (General, objectives, etc)

## Usage

``` r
codeDescriptionType
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
knitr::kable(head(codeDescriptionType, 10))
}
#> 
#> 
#> | code|name          |description                                                                                   |category |url |status |
#> |----:|:-------------|:---------------------------------------------------------------------------------------------|:--------|:---|:------|
#> |    1|General       |Unstructured, long description of the activity                                                |NA       |NA  |active |
#> |    2|Objectives    |Specific objectives for the activity, e.g. taken from logical framework                       |NA       |NA  |active |
#> |    3|Target Groups |Details of groups that are intended to benefit from the activity                              |NA       |NA  |active |
#> |    4|Other         |For miscellaneous use. A further classification or breakdown may be included in the narrative |NA       |NA  |active |
```
