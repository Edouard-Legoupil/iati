# codeSectorVocabulary

This is a Non-Core codelist.

## Usage

``` r
codeSectorVocabulary
```

## Format

A data frame with 13 rows and 6 variables:

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

<https://iatistandard.org/en/iati-standard/203/codelists/sectorvocabulary/>

## Examples

``` r
{
knitr::kable(head(codeSectorVocabulary, 10))
}
#> 
#> 
#> | code|name                                                                        |description                                                                                                         |category |url                                                                                                                  |status |
#> |----:|:---------------------------------------------------------------------------|:-------------------------------------------------------------------------------------------------------------------|:--------|:--------------------------------------------------------------------------------------------------------------------|:------|
#> |    1|OECD DAC CRS Purpose Codes (5 digit)                                        |The sector reported corresponds to an OECD DAC CRS 5-digit purpose code                                             |NA       |http://reference.iatistandard.org/codelists/Sector/                                                                  |active |
#> |    2|OECD DAC CRS Purpose Codes (3 digit)                                        |The sector reported corresponds to an OECD DAC CRS 3-digit purpose code                                             |NA       |http://reference.iatistandard.org/codelists/SectorCategory/                                                          |active |
#> |    3|Classification of the Functions of Government (UN)                          |The sector reported corresponds to the UN Classification of the Functions of Government (CoFoG)                     |NA       |http://unstats.un.org/unsd/cr/registry/regcst.asp?Cl=4                                                               |active |
#> |    4|Statistical classification of economic activities in the European Community |The sector reported corresponds to the statistical classifications of economic activities in the European Community |NA       |http://ec.europa.eu/eurostat/ramon/nomenclatures/index.cfm?TargetUrl=LST_NOM_DTL&StrNom=NACE_REV2&StrLanguageCode=EN |active |
#> |    5|National Taxonomy for Exempt Entities (USA)                                 |The sector reported corresponds to the National Taxonomy for Exempt Entities (NTEE) - USA                           |NA       |http://nccs.urban.org/classification/NTEE.cfm                                                                        |active |
#> |    6|AidData                                                                     |The sector reported corresponds to AidData classifications                                                          |NA       |NA                                                                                                                   |active |
#> |    7|SDG Goal                                                                    |A value from the top-level list of UN sustainable development goals (SDGs) (e.g. ‘1’)                               |NA       |https://sustainabledevelopment.un.org/?menu=1300                                                                     |active |
#> |    8|SDG Target                                                                  |A value from the second-level list of UN sustainable development goals (SDGs) (e.g. ‘1.1’)                          |NA       |http://unstats.un.org/sdgs/indicators/indicators-list/                                                               |active |
#> |    9|SDG Indicator                                                               |A value from the second-level list of UN sustainable development (SDG) indicators                                   |NA       |http://unstats.un.org/sdgs/indicators/indicators-list/                                                               |active |
#> |   10|Humanitarian Global Clusters (Inter-Agency Standing Committee)              |The sector reported corresponds to an Inter-Agency Standard Committee Humanitarian Global Cluster code              |NA       |https://data.humdata.org/dataset/global-coordination-groups-beta                                                     |active |
```
