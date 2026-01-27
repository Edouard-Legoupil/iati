# codeAidTypeVocabulary

The AidTypeVocabulary codelist defines a range of external codelists
which themselves provide codes and descriptions for aid type. This is a
Non-Core codelist.

## Usage

``` r
codeAidTypeVocabulary
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

<https://iatistandard.org/en/iati-standard/203/codelists/>

## Examples

``` r
{
knitr::kable(head(codeAidTypeVocabulary, 10))
}
#> 
#> 
#> | code|name                        |description                                                                                                                                         |category |url                                                                                              |status |
#> |----:|:---------------------------|:---------------------------------------------------------------------------------------------------------------------------------------------------|:--------|:------------------------------------------------------------------------------------------------|:------|
#> |    1|OECD DAC                    |List of codes provided by the OECD DAC used to distinguish types of aid                                                                             |NA       |http://reference.iatistandard.org/codelists/AidType/                                             |active |
#> |    2|Earmarking Category         |This vocabulary has been created by IATI and is derived from the Grand Bargain Earmarking Modality codelist                                         |NA       |http://reference.iatistandard.org/codelists/EarmarkingCategory/                                  |active |
#> |    3|Earmarking Modality         |Codes A to L replicated directly from Grand Bargain document found in Annex 1 (pg.16)                                                               |NA       |https://reliefweb.int/sites/reliefweb.int/files/resources/Grand_Bargain_final_22_May_FINAL-2.pdf |active |
#> |    4|Cash and Voucher Modalities |This vocabulary has been created by IATI, following agreements and recommendations of the Tracking Cash and Voucher Assistance (CVA) Working Group. |NA       |http://reference.iatistandard.org/codelists/CashandVoucherModalities/                            |active |
```
