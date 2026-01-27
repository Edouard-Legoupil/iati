# codeUNSDGTargets

A value from the second-level list of UN sustainable development goals
(SDGs) (e.g. ‘1.1’) External URL:
https://unstats.un.org/sdgs/indicators/indicators-list/

## Usage

``` r
codeUNSDGTargets
```

## Format

A data frame with 169 rows and 6 variables:

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
knitr::kable(head(codeUNSDGTargets, 10))
}
#> 
#> 
#> |code |name                                                                                                                                                                                                                                                                                                                                                                      |description |category |url |status |
#> |:----|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:-----------|:--------|:---|:------|
#> |1.1  |By 2030, eradicate extreme poverty for all people everywhere, currently measured as people living on less than $1.25 a day                                                                                                                                                                                                                                                |NA          |NA       |NA  |active |
#> |1.2  |By 2030, reduce at least by half the proportion of men, women and children of all ages living in poverty in all its dimensions according to national definitions                                                                                                                                                                                                          |NA          |NA       |NA  |active |
#> |1.3  |Implement nationally appropriate social protection systems and measures for all, including floors, and by 2030 achieve substantial coverage of the poor and the vulnerable                                                                                                                                                                                                |NA          |NA       |NA  |active |
#> |1.4  |By 2030, ensure that all men and women, in particular the poor and the vulnerable, have equal rights to economic resources, as well as access to basic services, ownership and control over land and other forms of property, inheritance, natural resources, appropriate new technology and financial services, including microfinance                                   |NA          |NA       |NA  |active |
#> |1.5  |By 2030, build the resilience of the poor and those in vulnerable situations and reduce their exposure and vulnerability to climate-related extreme events and other economic, social and environmental shocks and disasters                                                                                                                                              |NA          |NA       |NA  |active |
#> |1.a  |Ensure significant mobilization of resources from a variety of sources, including through enhanced development cooperation, in order to provide adequate and predictable means for developing countries, in particular least developed countries, to implement programmes and policies to end poverty in all its dimensions                                               |NA          |NA       |NA  |active |
#> |1.b  |Create sound policy frameworks at the national, regional and international levels, based on pro-poor and gender-sensitive development strategies, to support accelerated investment in poverty eradication actions                                                                                                                                                        |NA          |NA       |NA  |active |
#> |2.1  |By 2030, end hunger and ensure access by all people, in particular the poor and people in vulnerable situations, including infants, to safe, nutritious and sufficient food all year round                                                                                                                                                                                |NA          |NA       |NA  |active |
#> |2.2  |By 2030, end all forms of malnutrition, including achieving, by 2025, the internationally agreed targets on stunting and wasting in children under 5 years of age, and address the nutritional needs of adolescent girls, pregnant and lactating women and older persons                                                                                                  |NA          |NA       |NA  |active |
#> |2.3  |By 2030, double the agricultural productivity and incomes of small-scale food producers, in particular women, indigenous peoples, family farmers, pastoralists and fishers, including through secure and equal access to land, other productive resources and inputs, knowledge, financial services, markets and opportunities for value addition and non-farm employment |NA          |NA       |NA  |active |
```
