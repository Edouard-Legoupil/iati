# sector

DATASET_DESCRIPTION

## Usage

``` r
dataSector
```

## Format

A data frame

- `iati_identifier`:

  character A globally unique identifier for the activity.

- `sector_vocabulary`:

  character COLUMN_DESCRIPTION

- `sector_vocabulary_uri`:

  logical COLUMN_DESCRIPTION

- `sector_code`:

  character COLUMN_DESCRIPTION

- `sector_pct`:

  character COLUMN_DESCRIPTION

- `sector_desc`:

  character COLUMN_DESCRIPTION

- `sector_vocabulary_name`:

  character COLUMN_DESCRIPTION

- `sector_vocabulary_description`:

  character COLUMN_DESCRIPTION

## Source

<https://iatistandard.org/en/iati-standard/203/>

## Examples

``` r
{
knitr::kable(head(dataSector, 10))
}
#> 
#> 
#> |iati_identifier       | sector_vocabulary|sector_vocabulary_uri |sector_code |sector_pct |sector_desc                               |sector_vocabulary_name               |sector_vocabulary_description                                           |
#> |:---------------------|-----------------:|:---------------------|:-----------|:----------|:-----------------------------------------|:------------------------------------|:-----------------------------------------------------------------------|
#> |XM-DAC-41121-2022     |                 1|NA                    |72010       |76.06      |Material relief assistance and services   |OECD DAC CRS Purpose Codes (5 digit) |The sector reported corresponds to an OECD DAC CRS 5-digit purpose code |
#> |XM-DAC-41121-2022     |                 1|NA                    |72011       |6.79       |Basic Health Care Services in Emergencies |OECD DAC CRS Purpose Codes (5 digit) |The sector reported corresponds to an OECD DAC CRS 5-digit purpose code |
#> |XM-DAC-41121-2022     |                 1|NA                    |72012       |5.28       |Education in emergencies                  |OECD DAC CRS Purpose Codes (5 digit) |The sector reported corresponds to an OECD DAC CRS 5-digit purpose code |
#> |XM-DAC-41121-2022     |                 1|NA                    |72050       |11.87      |Relief co-ordination and support services |OECD DAC CRS Purpose Codes (5 digit) |The sector reported corresponds to an OECD DAC CRS 5-digit purpose code |
#> |XM-DAC-41121-2022     |                12|NA                    |E02         |100        |Humanitarian Assistance                   |NA                                   |NA                                                                      |
#> |XM-DAC-41121-2022-AME |                 1|NA                    |72010       |92.68      |Material relief assistance and services   |OECD DAC CRS Purpose Codes (5 digit) |The sector reported corresponds to an OECD DAC CRS 5-digit purpose code |
#> |XM-DAC-41121-2022-AME |                 1|NA                    |72011       |.8         |Basic Health Care Services in Emergencies |OECD DAC CRS Purpose Codes (5 digit) |The sector reported corresponds to an OECD DAC CRS 5-digit purpose code |
#> |XM-DAC-41121-2022-AME |                 1|NA                    |72012       |.45        |Education in emergencies                  |OECD DAC CRS Purpose Codes (5 digit) |The sector reported corresponds to an OECD DAC CRS 5-digit purpose code |
#> |XM-DAC-41121-2022-AME |                 1|NA                    |72050       |6.07       |Relief co-ordination and support services |OECD DAC CRS Purpose Codes (5 digit) |The sector reported corresponds to an OECD DAC CRS 5-digit purpose code |
#> |XM-DAC-41121-2022-AME |                12|NA                    |E02         |100        |Humanitarian Assistance                   |NA                                   |NA                                                                      |
```
