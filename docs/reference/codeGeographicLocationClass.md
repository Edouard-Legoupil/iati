# codeGeographicLocationClass

This is a Non-Core codelist.

## Usage

``` r
codeGeographicLocationClass
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
knitr::kable(head(codeGeographicLocationClass, 10))
}
#> 
#> 
#> | code|name                        |description                                                                                                           |category |url |status |
#> |----:|:---------------------------|:---------------------------------------------------------------------------------------------------------------------|:--------|:---|:------|
#> |    1|Administrative Region       |The designated geographic location is an administrative region (state, county, province, district, municipality etc.) |NA       |NA  |active |
#> |    2|Populated Place             |The designated geographic location is a populated place (town, village, farm etc.)                                    |NA       |NA  |active |
#> |    3|Structure                   |The designated geopgraphic location is a structure (such as a school or a clinic)                                     |NA       |NA  |active |
#> |    4|Other Topographical Feature |The designated geographic location is a topographical feature, such as a mountain, a river, a forest                  |NA       |NA  |active |
```
