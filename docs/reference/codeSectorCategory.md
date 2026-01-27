# codeSectorCategory

DAC 3 Digit Sector External URL:
http://www.oecd.org/dac/stats/dacandcrscodelists.htm

## Usage

``` r
codeSectorCategory
```

## Format

A data frame with 44 rows and 6 variables:

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
knitr::kable(head(codeSectorCategory, 10))
}
#> 
#> 
#> | code|name                                                 |description                                                                                                                                                              |category |url |status |
#> |----:|:----------------------------------------------------|:------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:--------|:---|:------|
#> |  111|Education, Level Unspecified                         |The codes in this category are to be used only when level of education is unspecified or unknown (e.g. training of primary school teachers should be coded under 11220). |NA       |NA  |active |
#> |  112|Basic Education                                      |NA                                                                                                                                                                       |NA       |NA  |active |
#> |  113|Secondary Education                                  |NA                                                                                                                                                                       |NA       |NA  |active |
#> |  114|Post-Secondary Education                             |NA                                                                                                                                                                       |NA       |NA  |active |
#> |  121|Health, General                                      |NA                                                                                                                                                                       |NA       |NA  |active |
#> |  122|Basic Health                                         |NA                                                                                                                                                                       |NA       |NA  |active |
#> |  123|Non-communicable diseases (NCDs)                     |NA                                                                                                                                                                       |NA       |NA  |active |
#> |  130|Population Policies/Programmes & Reproductive Health |NA                                                                                                                                                                       |NA       |NA  |active |
#> |  140|Water Supply & Sanitation                            |NA                                                                                                                                                                       |NA       |NA  |active |
#> |  151|Government & Civil Society-general                   |N.B. Use code 51010 for general budget support.                                                                                                                          |NA       |NA  |active |
```
