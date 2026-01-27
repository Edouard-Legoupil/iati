# transaction

Transactions recording committed or actual funds flowing in or out of an
aid activity.

## Usage

``` r
dataTransaction
```

## Format

A data frame

- `iati_identifier`:

  character COLUMN_DESCRIPTION

- `transaction_ref`:

  character COLUMN_DESCRIPTION

- `transaction_humanitarian`:

  logical COLUMN_DESCRIPTION

- `transaction_type_code`:

  double COLUMN_DESCRIPTION

- `transaction_date`:

  double COLUMN_DESCRIPTION

- `transaction_value_currency`:

  character COLUMN_DESCRIPTION

- `transaction_value_date`:

  double COLUMN_DESCRIPTION

- `transaction_value`:

  double COLUMN_DESCRIPTION

- `transaction_description`:

  character COLUMN_DESCRIPTION

- `transaction_provider_org_type`:

  double COLUMN_DESCRIPTION

- `transaction_provider_org_ref`:

  character COLUMN_DESCRIPTION

- `transaction_provider_org`:

  character COLUMN_DESCRIPTION

- `transaction_aid_type_code_1`:

  character COLUMN_DESCRIPTION

- `transaction_aid_type_vocabulary_1`:

  double COLUMN_DESCRIPTION

- `transaction_aid_type_code_2`:

  character COLUMN_DESCRIPTION

- `transaction_aid_type_vocabulary_2`:

  double COLUMN_DESCRIPTION

- `transaction_value_USD`:

  double COLUMN_DESCRIPTION

- `transaction_type_name`:

  character COLUMN_DESCRIPTION

- `transaction_type_description`:

  character COLUMN_DESCRIPTION

- `provider_org_type_name`:

  character COLUMN_DESCRIPTION

- `provider_org_type_description`:

  character COLUMN_DESCRIPTION

- `aid_type1_name`:

  character COLUMN_DESCRIPTION

- `aid_type1_description`:

  character COLUMN_DESCRIPTION

- `earmarking_name`:

  character COLUMN_DESCRIPTION

- `earmarking_description`:

  character COLUMN_DESCRIPTION

- `aid_type_vocabulary1_name`:

  character COLUMN_DESCRIPTION

- `aid_type_vocabulary1_description`:

  character COLUMN_DESCRIPTION

- `aid_type_vocabulary2_name`:

  character COLUMN_DESCRIPTION

- `aid_type_vocabulary2_description`:

  character COLUMN_DESCRIPTION

## Source

<https://iatistandard.org/en/iati-standard/203/activity-standard/iati-activities/iati-activity/transaction/>

## Examples

``` r
{
knitr::kable(head(dataTransaction, 10))
}
#> 
#> 
#> |iati_identifier   |transaction_ref |transaction_humanitarian | transaction_type_code|transaction_date |transaction_value_currency |transaction_value_date | transaction_value| transaction_value_USD|transaction_description                          | transaction_provider_org_type|transaction_provider_org_ref |transaction_provider_org                                                                                   |transaction_aid_type_code_1 | transaction_aid_type_vocabulary_1|transaction_aid_type_code_2 | transaction_aid_type_vocabulary_2|transaction_type_name |transaction_type_description                                                                                                                                                  |provider_org_type_name |provider_org_type_description |aid_type1_name                                                                          |aid_type1_description                                                                                                                                                                                                                                                                                             |earmarking_name  |earmarking_description                                |aid_type_vocabulary1_name |aid_type_vocabulary1_description                                        |aid_type_vocabulary2_name |aid_type_vocabulary2_description                                                                            |
#> |:-----------------|:---------------|:------------------------|---------------------:|:----------------|:--------------------------|:----------------------|-----------------:|---------------------:|:------------------------------------------------|-----------------------------:|:----------------------------|:----------------------------------------------------------------------------------------------------------|:---------------------------|---------------------------------:|:---------------------------|---------------------------------:|:---------------------|:-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:----------------------|:-----------------------------|:---------------------------------------------------------------------------------------|:-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:----------------|:-----------------------------------------------------|:-------------------------|:-----------------------------------------------------------------------|:-------------------------|:-----------------------------------------------------------------------------------------------------------|
#> |XM-DAC-41121-2022 |F0081           |NA                       |                    11|2022-03-10       |EUR                        |2022-03-10             |           8.0e+06|           8988764.045|Ukraine Regional Refugee Response Plan (RUKRN22) |                            10|XM-DAC-6-4                   |AICS - Agenzia Italiana per la Cooperazione allo Sviluppo / Italian Agency for Cooperation and Development |B03                         |                                 1|2                           |                                 2|Incoming Commitment   |A firm, written obligation from a donor or provider to provide a specified amount of funds, under particular terms and conditions, reported by a recipient for this activity. |Government             |NA                            |Contributions to specific-purpose programmes and funds managed by implementing partners |In addition to their core-funded operations, international organisations, NGOs, PPPs and networks, both in provider and in third countries, set up programmes and funds with a specific sectoral, thematic or geographical focus. Donors’ bilateral contributions to such programmes and funds are recorded here. |Softly Earmarked |Any or all of the Earmarking Modality codes D,E or F. |OECD DAC                  |List of codes provided by the OECD DAC used to distinguish types of aid |Earmarking Category       |This vocabulary has been created by IATI and is derived from the Grand Bargain Earmarking Modality codelist |
#> |XM-DAC-41121-2022 |F0075           |NA                       |                    11|2022-03-22       |EUR                        |2022-03-22             |           7.5e+04|             82146.769|Ukraine Regional Refugee Response Plan (RUKRN22) |                            10|NA                           |Government of Estonia                                                                                      |B03                         |                                 1|2                           |                                 2|Incoming Commitment   |A firm, written obligation from a donor or provider to provide a specified amount of funds, under particular terms and conditions, reported by a recipient for this activity. |Government             |NA                            |Contributions to specific-purpose programmes and funds managed by implementing partners |In addition to their core-funded operations, international organisations, NGOs, PPPs and networks, both in provider and in third countries, set up programmes and funds with a specific sectoral, thematic or geographical focus. Donors’ bilateral contributions to such programmes and funds are recorded here. |Softly Earmarked |Any or all of the Earmarking Modality codes D,E or F. |OECD DAC                  |List of codes provided by the OECD DAC used to distinguish types of aid |Earmarking Category       |This vocabulary has been created by IATI and is derived from the Grand Bargain Earmarking Modality codelist |
#> |XM-DAC-41121-2022 |F0080           |NA                       |                    11|2022-03-10       |AUD                        |2022-03-10             |           1.0e+07|           7220216.606|Ukraine Regional Refugee Response Plan (RUKRN22) |                            10|AU-5                         |Australia - Department of  Foreign Affairs and Trade                                                       |B03                         |                                 1|2                           |                                 2|Incoming Commitment   |A firm, written obligation from a donor or provider to provide a specified amount of funds, under particular terms and conditions, reported by a recipient for this activity. |Government             |NA                            |Contributions to specific-purpose programmes and funds managed by implementing partners |In addition to their core-funded operations, international organisations, NGOs, PPPs and networks, both in provider and in third countries, set up programmes and funds with a specific sectoral, thematic or geographical focus. Donors’ bilateral contributions to such programmes and funds are recorded here. |Softly Earmarked |Any or all of the Earmarking Modality codes D,E or F. |OECD DAC                  |List of codes provided by the OECD DAC used to distinguish types of aid |Earmarking Category       |This vocabulary has been created by IATI and is derived from the Grand Bargain Earmarking Modality codelist |
#> |XM-DAC-41121-2022 |F0237           |NA                       |                    11|2022-08-05       |EUR                        |2022-08-05             |           5.0e+05|            507099.391|Ukraine Regional Refugee Response Plan (RUKRN22) |                            10|NA                           |Government of France                                                                                       |B03                         |                                 1|2                           |                                 2|Incoming Commitment   |A firm, written obligation from a donor or provider to provide a specified amount of funds, under particular terms and conditions, reported by a recipient for this activity. |Government             |NA                            |Contributions to specific-purpose programmes and funds managed by implementing partners |In addition to their core-funded operations, international organisations, NGOs, PPPs and networks, both in provider and in third countries, set up programmes and funds with a specific sectoral, thematic or geographical focus. Donors’ bilateral contributions to such programmes and funds are recorded here. |Softly Earmarked |Any or all of the Earmarking Modality codes D,E or F. |OECD DAC                  |List of codes provided by the OECD DAC used to distinguish types of aid |Earmarking Category       |This vocabulary has been created by IATI and is derived from the Grand Bargain Earmarking Modality codelist |
#> |XM-DAC-41121-2022 |F0301           |NA                       |                    11|2022-10-20       |EUR                        |2022-10-20             |           5.0e+03|              4844.962|Ukraine Regional Refugee Response Plan (RUKRN22) |                            10|NA                           |Government of Spain                                                                                        |B03                         |                                 1|2                           |                                 2|Incoming Commitment   |A firm, written obligation from a donor or provider to provide a specified amount of funds, under particular terms and conditions, reported by a recipient for this activity. |Government             |NA                            |Contributions to specific-purpose programmes and funds managed by implementing partners |In addition to their core-funded operations, international organisations, NGOs, PPPs and networks, both in provider and in third countries, set up programmes and funds with a specific sectoral, thematic or geographical focus. Donors’ bilateral contributions to such programmes and funds are recorded here. |Softly Earmarked |Any or all of the Earmarking Modality codes D,E or F. |OECD DAC                  |List of codes provided by the OECD DAC used to distinguish types of aid |Earmarking Category       |This vocabulary has been created by IATI and is derived from the Grand Bargain Earmarking Modality codelist |
#> |XM-DAC-41121-2022 |F0129           |NA                       |                    11|2022-04-07       |EUR                        |2022-04-07             |           4.0e+04|             44642.858|Ukraine Regional Refugee Response Plan (RUKRN22) |                            10|NA                           |Government of Bulgaria                                                                                     |B03                         |                                 1|2                           |                                 2|Incoming Commitment   |A firm, written obligation from a donor or provider to provide a specified amount of funds, under particular terms and conditions, reported by a recipient for this activity. |Government             |NA                            |Contributions to specific-purpose programmes and funds managed by implementing partners |In addition to their core-funded operations, international organisations, NGOs, PPPs and networks, both in provider and in third countries, set up programmes and funds with a specific sectoral, thematic or geographical focus. Donors’ bilateral contributions to such programmes and funds are recorded here. |Softly Earmarked |Any or all of the Earmarking Modality codes D,E or F. |OECD DAC                  |List of codes provided by the OECD DAC used to distinguish types of aid |Earmarking Category       |This vocabulary has been created by IATI and is derived from the Grand Bargain Earmarking Modality codelist |
#> |XM-DAC-41121-2022 |F0129           |NA                       |                    11|2022-12-15       |EUR                        |2022-12-15             |           4.0e+04|             42643.924|Ukraine Regional Refugee Response Plan (RUKRN22) |                            10|NA                           |Government of Bulgaria                                                                                     |B03                         |                                 1|2                           |                                 2|Incoming Commitment   |A firm, written obligation from a donor or provider to provide a specified amount of funds, under particular terms and conditions, reported by a recipient for this activity. |Government             |NA                            |Contributions to specific-purpose programmes and funds managed by implementing partners |In addition to their core-funded operations, international organisations, NGOs, PPPs and networks, both in provider and in third countries, set up programmes and funds with a specific sectoral, thematic or geographical focus. Donors’ bilateral contributions to such programmes and funds are recorded here. |Softly Earmarked |Any or all of the Earmarking Modality codes D,E or F. |OECD DAC                  |List of codes provided by the OECD DAC used to distinguish types of aid |Earmarking Category       |This vocabulary has been created by IATI and is derived from the Grand Bargain Earmarking Modality codelist |
#> |XM-DAC-41121-2022 |F0174           |NA                       |                    11|2022-05-19       |EUR                        |2022-05-19             |           4.0e+06|           4223864.836|Ukraine Regional Refugee Response Plan (RUKRN22) |                            10|ES-DIR3-EA0035768            |Government of Spain                                                                                        |B03                         |                                 1|2                           |                                 2|Incoming Commitment   |A firm, written obligation from a donor or provider to provide a specified amount of funds, under particular terms and conditions, reported by a recipient for this activity. |Government             |NA                            |Contributions to specific-purpose programmes and funds managed by implementing partners |In addition to their core-funded operations, international organisations, NGOs, PPPs and networks, both in provider and in third countries, set up programmes and funds with a specific sectoral, thematic or geographical focus. Donors’ bilateral contributions to such programmes and funds are recorded here. |Softly Earmarked |Any or all of the Earmarking Modality codes D,E or F. |OECD DAC                  |List of codes provided by the OECD DAC used to distinguish types of aid |Earmarking Category       |This vocabulary has been created by IATI and is derived from the Grand Bargain Earmarking Modality codelist |
#> |XM-DAC-41121-2022 |F0087           |NA                       |                    11|2022-03-16       |EUR                        |2022-03-16             |           3.0e+06|           3285870.756|Ukraine Regional Refugee Response Plan (RUKRN22) |                            10|XM-DAC-21-1                  |Ireland - Department of Foreign Affairs and Trade                                                          |B03                         |                                 1|2                           |                                 2|Incoming Commitment   |A firm, written obligation from a donor or provider to provide a specified amount of funds, under particular terms and conditions, reported by a recipient for this activity. |Government             |NA                            |Contributions to specific-purpose programmes and funds managed by implementing partners |In addition to their core-funded operations, international organisations, NGOs, PPPs and networks, both in provider and in third countries, set up programmes and funds with a specific sectoral, thematic or geographical focus. Donors’ bilateral contributions to such programmes and funds are recorded here. |Softly Earmarked |Any or all of the Earmarking Modality codes D,E or F. |OECD DAC                  |List of codes provided by the OECD DAC used to distinguish types of aid |Earmarking Category       |This vocabulary has been created by IATI and is derived from the Grand Bargain Earmarking Modality codelist |
#> |XM-DAC-41121-2022 |F0096           |NA                       |                    11|2022-03-18       |GBP                        |2022-03-18             |           2.5e+07|          32722513.089|Ukraine Regional Refugee Response Plan (RUKRN22) |                            10|GB-GOV-1                     |UK - Foreign, Commonwealth and Development Office                                                          |B03                         |                                 1|2                           |                                 2|Incoming Commitment   |A firm, written obligation from a donor or provider to provide a specified amount of funds, under particular terms and conditions, reported by a recipient for this activity. |Government             |NA                            |Contributions to specific-purpose programmes and funds managed by implementing partners |In addition to their core-funded operations, international organisations, NGOs, PPPs and networks, both in provider and in third countries, set up programmes and funds with a specific sectoral, thematic or geographical focus. Donors’ bilateral contributions to such programmes and funds are recorded here. |Softly Earmarked |Any or all of the Earmarking Modality codes D,E or F. |OECD DAC                  |List of codes provided by the OECD DAC used to distinguish types of aid |Earmarking Category       |This vocabulary has been created by IATI and is derived from the Grand Bargain Earmarking Modality codelist |
```
