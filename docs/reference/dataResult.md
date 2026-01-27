# dataResult

DATASET_DESCRIPTION

## Usage

``` r
dataResult
```

## Format

A data frame

- `iati_identifier`:

  character A globally unique identifier for the activity.

- `result_type`:

  double COLUMN_DESCRIPTION

- `result_title`:

  character COLUMN_DESCRIPTION

- `result_indicator_title`:

  character COLUMN_DESCRIPTION

- `result_indicator_measure`:

  double COLUMN_DESCRIPTION

- `result_indicator_aggregation_status`:

  character COLUMN_DESCRIPTION

- `result_indicator_ascending`:

  character COLUMN_DESCRIPTION

- `result_indicator_reference_code`:

  logical COLUMN_DESCRIPTION

- `result_indicator_reference_uri`:

  logical COLUMN_DESCRIPTION

- `result_indicator_reference_vocabulary`:

  logical COLUMN_DESCRIPTION

- `result_indicator_baseline_location_ref`:

  character COLUMN_DESCRIPTION

- `result_indicator_baseline_value`:

  character COLUMN_DESCRIPTION

- `result_indicator_baseline_year`:

  character COLUMN_DESCRIPTION

- `result_indicator_baseline_date`:

  logical COLUMN_DESCRIPTION

- `result_indicator_baseline_dimension_1`:

  character COLUMN_DESCRIPTION

- `result_indicator_baseline_dimension_value_1`:

  character COLUMN_DESCRIPTION

- `result_indicator_baseline_dimension_2`:

  character COLUMN_DESCRIPTION

- `result_indicator_baseline_dimension_value_2`:

  character COLUMN_DESCRIPTION

- `result_indicator_period_start`:

  character COLUMN_DESCRIPTION

- `result_indicator_period_end`:

  character COLUMN_DESCRIPTION

- `result_indicator_target_value`:

  character COLUMN_DESCRIPTION

- `result_indicator_target_location_ref`:

  character COLUMN_DESCRIPTION

- `result_indicator_target_dimension_1`:

  character COLUMN_DESCRIPTION

- `result_indicator_target_value_1`:

  character COLUMN_DESCRIPTION

- `result_indicator_target_dimension_2`:

  character COLUMN_DESCRIPTION

- `result_indicator_target_value_2`:

  character COLUMN_DESCRIPTION

- `result_indicator_actual_value`:

  character COLUMN_DESCRIPTION

- `result_indicator_actual_location_ref`:

  character COLUMN_DESCRIPTION

- `result_indicator_actual_dimension_1`:

  character COLUMN_DESCRIPTION

- `result_indicator_actual_value_1`:

  character COLUMN_DESCRIPTION

- `result_indicator_actual_dimension_2`:

  character COLUMN_DESCRIPTION

- `result_indicator_actual_value_2`:

  character COLUMN_DESCRIPTION

- `result_type_name`:

  character COLUMN_DESCRIPTION

- `result_type_description`:

  character COLUMN_DESCRIPTION

- `indicator_measure_name`:

  character COLUMN_DESCRIPTION

- `indicator_measure_description`:

  character COLUMN_DESCRIPTION

## Source

<https://iatistandard.org/en/iati-standard/203/>

## Examples

``` r
{
knitr::kable(head(dataResult, 10))
}
#> 
#> 
#> |iati_identifier           | result_type|result_aggregation_status |result_title                                                         |result_desc |result_indicator_title                                                                                                                                     | result_indicator_measure|result_indicator_aggregation_status |result_indicator_ascending |result_indicator_reference_code |result_indicator_reference_uri                                               |result_indicator_reference_vocabulary |result_indicator_baseline_value |result_indicator_baseline_year |result_indicator_baseline_location_ref |result_indicator_baseline_dimension_1 |result_indicator_baseline_dimension_value_1 |result_indicator_baseline_dimension_2 |result_indicator_baseline_dimension_value_2 |result_indicator_period_start |result_indicator_period_end |result_indicator_target_value |result_indicator_target_location_ref |result_indicator_target_dimension_1 |result_indicator_target_value_1 |result_indicator_target_dimension_2 |result_indicator_target_value_2 |result_indicator_actual_value |result_indicator_actual_location_ref |result_indicator_actual_dimension_1 |result_indicator_actual_value_1 |result_indicator_actual_dimension_2 |result_indicator_actual_value_2 |result_type_name |result_type_description                                                                                                                                           |indicator_measure_name |indicator_measure_description            |
#> |:-------------------------|-----------:|:-------------------------|:--------------------------------------------------------------------|:-----------|:----------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------:|:-----------------------------------|:--------------------------|:-------------------------------|:----------------------------------------------------------------------------|:-------------------------------------|:-------------------------------|:------------------------------|:--------------------------------------|:-------------------------------------|:-------------------------------------------|:-------------------------------------|:-------------------------------------------|:-----------------------------|:---------------------------|:-----------------------------|:------------------------------------|:-----------------------------------|:-------------------------------|:-----------------------------------|:-------------------------------|:-----------------------------|:------------------------------------|:-----------------------------------|:-------------------------------|:-----------------------------------|:-------------------------------|:----------------|:-----------------------------------------------------------------------------------------------------------------------------------------------------------------|:----------------------|:----------------------------------------|
#> |XM-DAC-41121-2022-AME-BRA |           2|NA                        |1. Outcome area: Access to territory, registration and documentation |NA          |1.3 Proportion of PoC with legally recognized identity documents or credentials [GCR 4.2.2].                                                               |                        2|0                                   |1                          |GCR 4.2.2                       |https://www.unhcr.org/media/global-compact-refugees-indicator-framework-2022 |99                                    |NA                              |NA                             |NA                                     |NA                                    |NA                                          |NA                                    |NA                                          |2022-01-01                    |2022-12-31                  |90                            |Brazil                               |Population Type                     |Refugees and Asylum-seekers     |NA                                  |NA                              |100                           |Brazil                               |Population Type                     |Refugees and Asylum-seekers     |NA                                  |NA                              |Outcome          |Results of the activity that produce an effect on the overall communities or issues you serve. For example lower rate of infection after a vaccination programme. |Percentage             |The indicator is measured in percentages |
#> |XM-DAC-41121-2022-AME-BRA |           2|NA                        |1. Outcome area: Access to territory, registration and documentation |NA          |1.2 Proportion of children under 5 years of age whose births have been registered with a civil authority. [SDG 16.9.1 - Tier 1]                            |                        2|0                                   |1                          |SDG 16.9.1                      |NA                                                                           |9                                     |NA                              |NA                             |NA                                     |NA                                    |NA                                          |NA                                    |NA                                          |2022-01-01                    |2022-12-31                  |80                            |Brazil                               |Population Type                     |Refugees and Asylum-seekers     |NA                                  |NA                              |92.99                         |Brazil                               |Population Type                     |Refugees and Asylum-seekers     |NA                                  |NA                              |Outcome          |Results of the activity that produce an effect on the overall communities or issues you serve. For example lower rate of infection after a vaccination programme. |Percentage             |The indicator is measured in percentages |
#> |XM-DAC-41121-2022-AME-BRA |           2|NA                        |1. Outcome area: Access to territory, registration and documentation |NA          |1.1 Proportion of refugees and asylum seekers registered on an individual basis.                                                                           |                        2|0                                   |1                          |NA                              |NA                                                                           |NA                                    |100                             |2021                           |Brazil                                 |Population Type                       |Refugees and Asylum-seekers                 |NA                                    |NA                                          |2022-01-01                    |2022-12-31                  |100                           |Brazil                               |Population Type                     |Refugees and Asylum-seekers     |NA                                  |NA                              |100                           |Brazil                               |Population Type                     |Refugees and Asylum-seekers     |NA                                  |NA                              |Outcome          |Results of the activity that produce an effect on the overall communities or issues you serve. For example lower rate of infection after a vaccination programme. |Percentage             |The indicator is measured in percentages |
#> |XM-DAC-41121-2022-AME-BRA |           2|NA                        |2. Outcome area: Status determination                                |NA          |2.3 Proportion of individuals undergoing asylum procedures who have access to an effective appeal mechanism after first instance rejection of their claim. |                        2|0                                   |1                          |NA                              |NA                                                                           |NA                                    |100                             |2021                           |Brazil                                 |Population Type                       |Refugees and Asylum-seekers                 |NA                                    |NA                                          |2022-01-01                    |2022-12-31                  |100                           |Brazil                               |Population Type                     |Refugees and Asylum-seekers     |NA                                  |NA                              |100                           |Brazil                               |Population Type                     |Refugees and Asylum-seekers     |NA                                  |NA                              |Outcome          |Results of the activity that produce an effect on the overall communities or issues you serve. For example lower rate of infection after a vaccination programme. |Percentage             |The indicator is measured in percentages |
#> |XM-DAC-41121-2022-AME-BRA |           2|NA                        |2. Outcome area: Status determination                                |NA          |2.2 Proportion of individuals undergoing asylum procedures who have access to legal advice or representation.                                              |                        2|0                                   |1                          |NA                              |NA                                                                           |NA                                    |100                             |2021                           |Brazil                                 |Population Type                       |Refugees and Asylum-seekers                 |NA                                    |NA                                          |2022-01-01                    |2022-12-31                  |100                           |Brazil                               |Population Type                     |Refugees and Asylum-seekers     |NA                                  |NA                              |100                           |Brazil                               |Population Type                     |Refugees and Asylum-seekers     |NA                                  |NA                              |Outcome          |Results of the activity that produce an effect on the overall communities or issues you serve. For example lower rate of infection after a vaccination programme. |Percentage             |The indicator is measured in percentages |
#> |XM-DAC-41121-2022-AME-BRA |           2|NA                        |2. Outcome area: Status determination                                |NA          |2.1 Average processing time (in days) from registration to first instance asylum decision (disaggregated by individual and group procedures).              |                        1|0                                   |0                          |NA                              |NA                                                                           |NA                                    |1763                            |2021                           |Brazil                                 |Population Type                       |Refugees and Asylum-seekers                 |NA                                    |NA                                          |2022-01-01                    |2022-12-31                  |1763                          |Brazil                               |Population Type                     |Refugees and Asylum-seekers     |NA                                  |NA                              |1577                          |Brazil                               |Population Type                     |Refugees and Asylum-seekers     |NA                                  |NA                              |Outcome          |Results of the activity that produce an effect on the overall communities or issues you serve. For example lower rate of infection after a vaccination programme. |Unit                   |The indicator is measured in units.      |
#> |XM-DAC-41121-2022-AME-BRA |           2|NA                        |4. Outcome area: Gender-based violence                               |NA          |4.2 Proportion of POCs who do not accept violence against women.                                                                                           |                        2|0                                   |1                          |NA                              |NA                                                                           |NA                                    |NA                              |NA                             |NA                                     |NA                                    |NA                                          |NA                                    |NA                                          |2022-01-01                    |2022-12-31                  |60                            |Brazil                               |Population Type                     |Refugees and Asylum-seekers     |NA                                  |NA                              |97                            |Brazil                               |Population Type                     |Refugees and Asylum-seekers     |NA                                  |NA                              |Outcome          |Results of the activity that produce an effect on the overall communities or issues you serve. For example lower rate of infection after a vaccination programme. |Percentage             |The indicator is measured in percentages |
#> |XM-DAC-41121-2022-AME-BRA |           2|NA                        |4. Outcome area: Gender-based violence                               |NA          |4.1 Proportion of PoC who know where to access available GBV services                                                                                      |                        2|0                                   |1                          |NA                              |NA                                                                           |NA                                    |NA                              |NA                             |NA                                     |NA                                    |NA                                          |NA                                    |NA                                          |2022-01-01                    |2022-12-31                  |71                            |Brazil                               |Population Type                     |Refugees and Asylum-seekers     |NA                                  |NA                              |89.01                         |Brazil                               |Population Type                     |Refugees and Asylum-seekers     |NA                                  |NA                              |Outcome          |Results of the activity that produce an effect on the overall communities or issues you serve. For example lower rate of infection after a vaccination programme. |Percentage             |The indicator is measured in percentages |
#> |XM-DAC-41121-2022-AME-BRA |           2|NA                        |7. Outcome area: Community engagement and women's empowerment        |NA          |7.1 Proportion of PoC who participate meaningfully across all phases of the OMC.                                                                           |                        2|0                                   |1                          |NA                              |NA                                                                           |NA                                    |100                             |2021                           |Brazil                                 |Population Type                       |Refugees and Asylum-seekers                 |NA                                    |NA                                          |2022-01-01                    |2022-12-31                  |100                           |Brazil                               |Population Type                     |Refugees and Asylum-seekers     |NA                                  |NA                              |100                           |Brazil                               |Population Type                     |Refugees and Asylum-seekers     |NA                                  |NA                              |Outcome          |Results of the activity that produce an effect on the overall communities or issues you serve. For example lower rate of infection after a vaccination programme. |Percentage             |The indicator is measured in percentages |
#> |XM-DAC-41121-2022-AME-BRA |           2|NA                        |7. Outcome area: Community engagement and women's empowerment        |NA          |7.2 Proportion of PoC who have access to effective feedback and response mechanisms.                                                                       |                        2|0                                   |1                          |NA                              |NA                                                                           |NA                                    |98.99                           |2021                           |Brazil                                 |Population Type                       |Refugees and Asylum-seekers                 |NA                                    |NA                                          |2022-01-01                    |2022-12-31                  |100                           |Brazil                               |Population Type                     |Refugees and Asylum-seekers     |NA                                  |NA                              |99.43                         |Brazil                               |Population Type                     |Refugees and Asylum-seekers     |NA                                  |NA                              |Outcome          |Results of the activity that produce an effect on the overall communities or issues you serve. For example lower rate of infection after a vaccination programme. |Percentage             |The indicator is measured in percentages |
```
