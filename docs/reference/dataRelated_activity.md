# dataRelated_activity

DATASET_DESCRIPTION

## Usage

``` r
dataRelated_activity
```

## Format

A data frame

- `iati_identifier`:

  character A globally unique identifier for the activity.

- `related_activity_ref`:

  character COLUMN_DESCRIPTION

- `related_activity_type`:

  character COLUMN_DESCRIPTION

## Source

<https://iatistandard.org/en/iati-standard/203/>

## Examples

``` r
{
knitr::kable(head(dataRelated_activity, 10))
}
#> 
#> 
#> |iati_identifier   |related_activity_ref         |related_activity_type |
#> |:-----------------|:----------------------------|:---------------------|
#> |XM-DAC-41121-2022 |XM-DAC-41121-2022-AME        |2                     |
#> |XM-DAC-41121-2022 |XM-DAC-41121-2022-ASO        |2                     |
#> |XM-DAC-41121-2022 |XM-DAC-41121-2022-EHGL       |2                     |
#> |XM-DAC-41121-2022 |XM-DAC-41121-2022-EUR        |2                     |
#> |XM-DAC-41121-2022 |XM-DAC-41121-2022-GLOBALPROG |2                     |
#> |XM-DAC-41121-2022 |XM-DAC-41121-2022-HQ         |2                     |
#> |XM-DAC-41121-2022 |XM-DAC-41121-2022-JPO        |2                     |
#> |XM-DAC-41121-2022 |XM-DAC-41121-2022-MENA       |2                     |
#> |XM-DAC-41121-2022 |XM-DAC-41121-2022-SAO        |2                     |
#> |XM-DAC-41121-2022 |XM-DAC-41121-2022-WCA        |2                     |
```
