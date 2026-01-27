# codeCountry

The Country codelist is generated from the ISO 3166-1 part of the ISO
3166 standard. The standard makes allowance, alongside the officially
assigned codes, for code elements to be expanded by using either
reserved codes or user-assigned codes. IATI currently defines additional
codes in the XA -XZ range. External URL:
http://www.iso.org/iso/home/standards/country_codes.htm

## Usage

``` r
codeCountry
```

## Format

A data frame with 251 rows and 6 variables:

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
knitr::kable(head(codeCountry, 10))
}
#> 
#> 
#> |code |name                |description |category |url |status |
#> |:----|:-------------------|:-----------|:--------|:---|:------|
#> |AF   |Afghanistan         |NA          |NA       |NA  |active |
#> |AX   |Åland Islands       |NA          |NA       |NA  |active |
#> |AL   |Albania             |NA          |NA       |NA  |active |
#> |DZ   |Algeria             |NA          |NA       |NA  |active |
#> |AS   |American Samoa      |NA          |NA       |NA  |active |
#> |AD   |Andorra             |NA          |NA       |NA  |active |
#> |AO   |Angola              |NA          |NA       |NA  |active |
#> |AI   |Anguilla            |NA          |NA       |NA  |active |
#> |AQ   |Antarctica          |NA          |NA       |NA  |active |
#> |AG   |Antigua and Barbuda |NA          |NA       |NA  |active |
```
