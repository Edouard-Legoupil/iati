# dataDefault_aid_type

Default_aid_type

## Usage

``` r
dataDefault_aid_type
```

## Format

A data frame

- `iati_identifier`:

  character A globally unique identifier for the activity.

- `default_aid_type_code`:

  character aid_type_code

- `default_aid_type_vocabulary`:

  logical aid_type_vocabulary

## Source

<https://iatistandard.org/en/iati-standard/203/>

## Examples

``` r
{
knitr::kable(head(dataDefault_aid_type, 10))
}
#> 
#> 
#> |iati_identifier              |default_aid_type_code |default_aid_type_vocabulary |
#> |:----------------------------|:---------------------|:---------------------------|
#> |XM-DAC-41121-2022            |B02                   |NA                          |
#> |XM-DAC-41121-2022-AME        |B02                   |NA                          |
#> |XM-DAC-41121-2022-ASO        |B02                   |NA                          |
#> |XM-DAC-41121-2022-EHGL       |B02                   |NA                          |
#> |XM-DAC-41121-2022-EUR        |B02                   |NA                          |
#> |XM-DAC-41121-2022-MENA       |B02                   |NA                          |
#> |XM-DAC-41121-2022-SAO        |B02                   |NA                          |
#> |XM-DAC-41121-2022-WCA        |B02                   |NA                          |
#> |XM-DAC-41121-2022-AME-ARGMCO |B02                   |NA                          |
#> |XM-DAC-41121-2022-AME-BRA    |B02                   |NA                          |
```
