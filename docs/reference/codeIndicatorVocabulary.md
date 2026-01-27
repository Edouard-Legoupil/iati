# codeIndicatorVocabulary

The Indicator Vocabulary codelist defines a range of external codelists
which themselves provide codes and descriptions for indicators, for
example to specify results.

## Usage

``` r
codeIndicatorVocabulary
```

## Format

A data frame with 10 rows and 6 variables:

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
knitr::kable(head(codeIndicatorVocabulary, 10))
}
#> 
#> 
#> | code|name                                              |description |category |url                                                                        |status |
#> |----:|:-------------------------------------------------|:-----------|:--------|:--------------------------------------------------------------------------|:------|
#> |    1|WHO Registry                                      |NA          |NA       |http://apps.who.int/gho/indicatorregistry/App_Main/indicator_registry.aspx |active |
#> |    2|Sphere Handbook                                   |NA          |NA       |http://www.spherehandbook.org                                              |active |
#> |    3|US Foreign Assistance Framework                   |NA          |NA       |http://www.state.gov/s/d/rm/rls/dosstrat/2007/html/82981.htm               |active |
#> |    4|World Bank World Development Indicators           |NA          |NA       |http://data.worldbank.org/data-catalog/world-development-indicators        |active |
#> |    5|UN Millennium Development Goals Indicators        |NA          |NA       |http://mdgs.un.org/unsd/mdg/Host.aspx?Content=Indicators/OfficialList.htm  |active |
#> |    6|UNOCHA Humanitarian Response Indicators           |NA          |NA       |https://www.humanitarianresponse.info/applications/ir/indicators           |active |
#> |    7|HIV/AIDS Indicator Registry                       |NA          |NA       |http://www.indicatorregistry.org                                           |active |
#> |    8|Harmonized Indicators for Private Sector (HIPSO)  |NA          |NA       |https://indicators.ifipartnership.org/indicators/                          |active |
#> |    9|UN Sustainable Development Goals (SDG) Indicators |NA          |NA       |https://unstats.un.org/sdgs/indicators/indicators-list/                    |active |
#> |   99|Reporting Organisation                            |NA          |NA       |NA                                                                         |active |
```
