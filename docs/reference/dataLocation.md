# dataLocation

DATASET_DESCRIPTION

## Usage

``` r
dataLocation
```

## Format

A data frame

- `iati_identifier`:

  character A globally unique identifier for the activity.

- `location_ref`:

  character COLUMN_DESCRIPTION

- `location_reach`:

  character COLUMN_DESCRIPTION

- `location_id_vocabulary`:

  logical COLUMN_DESCRIPTION

- `location_id_code`:

  logical COLUMN_DESCRIPTION

- `location_name`:

  character COLUMN_DESCRIPTION

- `location_type`:

  character COLUMN_DESCRIPTION

- `location_activity_descr`:

  logical COLUMN_DESCRIPTION

- `location_adm_vocabulary`:

  logical COLUMN_DESCRIPTION

- `location_adm_level`:

  logical COLUMN_DESCRIPTION

- `location_adm_code`:

  logical COLUMN_DESCRIPTION

- `location_lat`:

  character COLUMN_DESCRIPTION

- `location_long`:

  character COLUMN_DESCRIPTION

- `location_exactness_code`:

  character COLUMN_DESCRIPTION

- `location_class_code`:

  character COLUMN_DESCRIPTION

- `location_feature_designation_code`:

  logical COLUMN_DESCRIPTION

## Source

<https://iatistandard.org/en/iati-standard/203/>

## Examples

``` r
{
knitr::kable(head(dataLocation, 10))
}
#> 
#> 
#> |iati_identifier        |location_ref |location_reach_code |location_id_vocabulary |location_id_code |location_name |location_type         |location_activity_descr |location_adm_vocabulary |location_adm_level |location_adm_code |location_lat |location_long |location_exactness_code |location_class_code |location_feature_designation_code |
#> |:----------------------|:------------|:-------------------|:----------------------|:----------------|:-------------|:---------------------|:-----------------------|:-----------------------|:------------------|:-----------------|:------------|:-------------|:-----------------------|:-------------------|:---------------------------------|
#> |XM-DAC-41121-2022      |CHEP000332   |1                   |NA                     |NA               |HQ Geneva     |UNHCR Headquarters    |NA                      |NA                      |NA                 |NA                |46.2204      |6.1412        |1                       |3                   |NA                                |
#> |XM-DAC-41121-2022-AME  |PANP000747   |1                   |NA                     |NA               |Panamá        |UNHCR Regional Bureau |NA                      |NA                      |NA                 |NA                |9.0029       |-79.5172      |1                       |3                   |NA                                |
#> |XM-DAC-41121-2022-ASO  |THAP000346   |1                   |NA                     |NA               |Bangkok       |UNHCR Regional Bureau |NA                      |NA                      |NA                 |NA                |13.7438      |100.5479      |1                       |3                   |NA                                |
#> |XM-DAC-41121-2022-EHGL |ETHp000134   |1                   |NA                     |NA               |Addis Ababa   |UNHCR Country Office  |NA                      |NA                      |NA                 |NA                |8.9928       |38.7833       |1                       |3                   |NA                                |
#> |XM-DAC-41121-2022-EHGL |ERIp000131   |1                   |NA                     |NA               |Asmara        |UNHCR Country Office  |NA                      |NA                      |NA                 |NA                |15.3318      |38.9338       |1                       |3                   |NA                                |
#> |XM-DAC-41121-2022-EHGL |BDIp000070   |1                   |NA                     |NA               |Bujumbura     |UNHCR Country Office  |NA                      |NA                      |NA                 |NA                |-3.3891      |29.3533       |1                       |3                   |NA                                |
#> |XM-DAC-41121-2022-EHGL |TZAp000339   |1                   |NA                     |NA               |Dar Es Salam  |UNHCR Country Office  |NA                      |NA                      |NA                 |NA                |-6.816       |39.278        |1                       |3                   |NA                                |
#> |XM-DAC-41121-2022-EHGL |DJIp000121   |1                   |NA                     |NA               |Djibouti      |UNHCR Country Office  |NA                      |NA                      |NA                 |NA                |11.595       |43.142        |1                       |3                   |NA                                |
#> |XM-DAC-41121-2022-EHGL |SSDp000542   |1                   |NA                     |NA               |Juba          |UNHCR Country Office  |NA                      |NA                      |NA                 |NA                |4.8511       |31.5978       |1                       |3                   |NA                                |
#> |XM-DAC-41121-2022-EHGL |UGAp000362   |1                   |NA                     |NA               |Kampala       |UNHCR Country Office  |NA                      |NA                      |NA                 |NA                |0.3348       |32.5967       |1                       |3                   |NA                                |
```
