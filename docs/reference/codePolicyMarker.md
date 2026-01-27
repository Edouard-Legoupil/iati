# codePolicyMarker

The Policy Marker codelist is derived from the policy markers declared
by the WP-STAT. The codes themselves are created by IATI. External URL:
http://www.oecd.org/dac/stats/dacandcrscodelists.htm

## Usage

``` r
codePolicyMarker
```

## Format

A data frame with 12 rows and 6 variables:

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
knitr::kable(head(codePolicyMarker, 10))
}
#> 
#> 
#> | code|name                                                                                    |description |category |url |status |
#> |----:|:---------------------------------------------------------------------------------------|:-----------|:--------|:---|:------|
#> |    1|Gender Equality                                                                         |NA          |NA       |NA  |active |
#> |    2|Aid to Environment                                                                      |NA          |NA       |NA  |active |
#> |    3|Participatory Development/Good Governance                                               |NA          |NA       |NA  |active |
#> |    4|Trade Development                                                                       |NA          |NA       |NA  |active |
#> |    5|Aid Targeting the Objectives of the Convention on Biological Diversity                  |NA          |NA       |NA  |active |
#> |    6|Aid Targeting the Objectives of the Framework Convention on Climate Change - Mitigation |NA          |NA       |NA  |active |
#> |    7|Aid Targeting the Objectives of the Framework Convention on Climate Change - Adaptation |NA          |NA       |NA  |active |
#> |    8|Aid Targeting the Objectives of the Convention to Combat Desertification                |NA          |NA       |NA  |active |
#> |    9|Reproductive, Maternal, Newborn and Child Health (RMNCH)                                |NA          |NA       |NA  |active |
#> |   10|Disaster Risk Reduction(DRR)                                                            |NA          |NA       |NA  |active |
```
