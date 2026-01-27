# codeFlowType

DAC/CRS distinction between ODA (official development assistance) and
other types of resource flow. External URL:
http://www.oecd.org/dac/stats/dacandcrscodelists.htm

## Usage

``` r
codeFlowType
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
knitr::kable(head(codeFlowType, 10))
}
#> 
#> 
#> | code|name                                |description                                                                                                                                      |category |url |status    |
#> |----:|:-----------------------------------|:------------------------------------------------------------------------------------------------------------------------------------------------|:--------|:---|:---------|
#> |   10|ODA                                 |Official Development Assistance                                                                                                                  |NA       |NA  |active    |
#> |   20|OOF                                 |Other Official Flows                                                                                                                             |NA       |NA  |withdrawn |
#> |   21|Non-export credit OOF               |Other Official Flows, excl. export credits                                                                                                       |NA       |NA  |active    |
#> |   22|Officially supported export credits |Officially supported export credits. Covers both official direct export credits and private export credits under official guarantee or insurance |NA       |NA  |active    |
#> |   30|Private Development Finance         |Financing by civil society organisations (NGOs, philantropic foundations, etc.)                                                                  |NA       |NA  |active    |
#> |   35|Private Market                      |Private long-term (i.e. over one-year maturity) capital transactions made by residents of DAC countries                                          |NA       |NA  |withdrawn |
#> |   36|Private Foreign Direct Investment   |Private Foreign Direct Investment                                                                                                                |NA       |NA  |active    |
#> |   37|Other Private flows at market terms |Private long-term (i.e. over one-year maturity) capital transactions made by residents of DAC countries                                          |NA       |NA  |active    |
#> |   40|Non flow                            |e.g. GNI, ODA%GNI, Population etc                                                                                                                |NA       |NA  |active    |
#> |   50|Other flows                         |e.g. non-ODA component of peacebuilding operations                                                                                               |NA       |NA  |active    |
```
