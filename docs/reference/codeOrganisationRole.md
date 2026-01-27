# codeOrganisationRole

IATI codes for the role of an organisation within an activity. An
organisation can play more than one role within an activity. This is a
Core codelist.

## Usage

``` r
codeOrganisationRole
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

<https://iatistandard.org/en/iati-standard/203/codelists/organisationrole/>

## Examples

``` r
{
knitr::kable(head(codeOrganisationRole, 10))
}
#> 
#> 
#> | code|name         |description                                                                                                |category |url |status |
#> |----:|:------------|:----------------------------------------------------------------------------------------------------------|:--------|:---|:------|
#> |    1|Funding      |The government or organisation which provides funds to the activity.                                       |NA       |NA  |active |
#> |    2|Accountable  |An organisation responsible for oversight of the activity and its outcomes                                 |NA       |NA  |active |
#> |    3|Extending    |An organisation that manages the budget and direction of an activity on behalf of the funding organisation |NA       |NA  |active |
#> |    4|Implementing |The organisation that physically carries out the activity or intervention.                                 |NA       |NA  |active |
```
