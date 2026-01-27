# codeEarmarkingCategory

This codelist has been created by IATI and is derived from the Grand
Bargain Earmarking Modality codelist. See:
https://reliefweb.int/sites/reliefweb.int/files/resources/Grand_Bargain_final_22_May_FINAL-2.pdf

## Usage

``` r
codeEarmarkingCategory
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

<https://iatistandard.org/en/iati-standard/203/codelists/earmarkingcategory/>

## Examples

``` r
{
knitr::kable(head(codeEarmarkingCategory, 10))
}
#> 
#> 
#> | code|name              |description                                           |category |url |status |
#> |----:|:-----------------|:-----------------------------------------------------|:--------|:---|:------|
#> |    1|Unearmarked       |Any or all of the Earmarking Modality codes A,B or C. |NA       |NA  |active |
#> |    2|Softly Earmarked  |Any or all of the Earmarking Modality codes D,E or F. |NA       |NA  |active |
#> |    3|Earmarked         |Any or all of the Earmarking Modality codes G or H.   |NA       |NA  |active |
#> |    4|Tightly Earmarked |Any or all of the Earmarking Modality codes I,J or K. |NA       |NA  |active |
```
