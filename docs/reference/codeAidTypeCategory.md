# codeAidTypeCategory

This codelists exists to group the Aid Type codelist into categories. It
is not used as a codelist in its own right. External URL:
http://www.oecd.org/dac/stats/dacandcrscodelists.htm

## Usage

``` r
codeAidTypeCategory
```

## Format

A data frame with 8 rows and 6 variables:

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
knitr::kable(head(codeAidTypeCategory, 10))
}
#> 
#> 
#> |code |name                                               |description                                                                                                                                                                                                                                                                                                                                                        |category |url |status |
#> |:----|:--------------------------------------------------|:------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:--------|:---|:------|
#> |A    |Budget support                                     |For contributions under this category, the donor relinquishes the exclusive control of its funds by sharing the responsibility with the recipient.                                                                                                                                                                                                                 |NA       |NA  |active |
#> |B    |Core contributions and pooled programmes and funds |For contributions under this category, the donor relinquishes the exclusive control of its funds by sharing the responsibility with other stakeholders (other donors, NGOs, multilateral institutions, Public Private Partnerships). The category covers both core contributions (B01 and B02), and pooled contributions with a specific earmarking (B03 and B04). |NA       |NA  |active |
#> |C    |Project-type interventions                         |N.B. Within this category, members able to do so are requested to report the aggregate amount used for financing donor experts/consultants on Table DAC11. Where the activity consists solely of experts’ costs, report under category D.                                                                                                                          |NA       |NA  |active |
#> |D    |Experts and other technical assistance             |This category covers the provision, outside projects as described in category C, of know-how in the form of personnel, training and research.                                                                                                                                                                                                                      |NA       |NA  |active |
#> |E    |Scholarships and student costs in donor countries  |NA                                                                                                                                                                                                                                                                                                                                                                 |NA       |NA  |active |
#> |F    |Debt relief                                        |NA                                                                                                                                                                                                                                                                                                                                                                 |NA       |NA  |active |
#> |G    |Administrative costs not included elsewhere        |NA                                                                                                                                                                                                                                                                                                                                                                 |NA       |NA  |active |
#> |H    |Other in-donor expenditures                        |Groups a number of contributions that do not give rise to a cross-border flow.                                                                                                                                                                                                                                                                                     |NA       |NA  |active |
```
