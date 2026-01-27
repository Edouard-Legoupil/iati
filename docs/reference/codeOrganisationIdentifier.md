# codeOrganisationIdentifier

As of 1.04 this list is no longer maintained.
http://support.iatistandard.org/entries/28497976-Retire-the-Organisation-Identifier-codelist#view-post-25368673
For general guidance about constructing Organisation Identifiers, please
see http://iatistandard.org/organisation-identifiers/

## Usage

``` r
codeOrganisationIdentifier
```

## Format

A data frame with 419 rows and 6 variables:

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
knitr::kable(head(codeOrganisationIdentifier, 10))
}
#> 
#> 
#> |code  |name                                      |description |category |url |status |
#> |:-----|:-----------------------------------------|:-----------|:--------|:---|:------|
#> |AT-1  |Federal Ministry of Finance               |NA          |NA       |NA  |active |
#> |AT-10 |Ministry for Agriculture and Environment  |NA          |NA       |NA  |active |
#> |AT-11 |Ministry of Defense                       |NA          |NA       |NA  |active |
#> |AT-12 |Ministry of Interior                      |NA          |NA       |NA  |active |
#> |AT-2  |Various ministries                        |NA          |NA       |NA  |active |
#> |AT-3  |Federal Government of Austria             |NA          |NA       |NA  |active |
#> |AT-4  |Oesterreichische Kontrollbank AG          |NA          |NA       |NA  |active |
#> |AT-5  |Federal Ministry of Foreign Affairs       |NA          |NA       |NA  |active |
#> |AT-6  |Provincial governments, local communities |NA          |NA       |NA  |active |
#> |AT-8  |Austrian Development Agency               |NA          |NA       |NA  |active |
```
