# dataActivity

Records of all activities since UNHCR Programme 2016 in IATI format

## Usage

``` r
dataActivity
```

## Format

A data frame with 825 rows and 45 variables:

- `iati_identifier`:

  character A globally unique identifier for the activity.

- `reporting_org`:

  character The organisation issuing the report. May be a primary source
  (reporting on its own activity as donor, implementing agency, etc) or
  a secondary source (reporting on the activities of another
  organisation).

- `reporting_org_ref`:

  character Machine-readable identification string for the organisation
  issuing the report. Must be in the format
  RegistrationAgency-RegistrationNumber where RegistrationAgency is a
  valid code in the Organisation Registration Agency code list and
  RegistrationNumber is a valid identifier issued by the
  RegistrationAgency.

- `reporting_org_type`:

  character The type of organisation issuing the report. See IATI
  codelist for values.

- `reporting_org_secondary_reporter`:

  logical A flag indicating that the reporting organisation of this
  activity is acting as a secondary reporter. A secondary reporter is
  one that reproduces data on the activities of an organisation for
  which it is not directly responsible. This does not include a
  publisher officially assigned as a proxy to report on behalf of
  another.

- `title_eng`:

  character A short, human-readable title that contains a meaningful
  summary of the activity. English

- `title_fr`:

  character A short, human-readable title that contains a meaningful
  summary of the activity. French

- `title_es`:

  character A short, human-readable title that contains a meaningful
  summary of the activity. Spanish

- `title_zh`:

  character A short, human-readable title that contains a meaningful
  summary of the activity. Chinese

- `title_ru`:

  character A short, human-readable title that contains a meaningful
  summary of the activity. Russian

- `title_ar`:

  character A short, human-readable title that contains a meaningful
  summary of the activity. Arabic

- `description_type_1`:

  character The type of description being provided. This is not required
  if only one general description of the activity is reported.

- `description_eng_1`:

  character Description type 1 - English

- `descriptionv_fr_1`:

  character Description type 1 - French

- `description_type_2`:

  character COLUMN_DESCRIPTION

- `description_eng_2`:

  character COLUMN_DESCRIPTION

- `descriptionv_fr_2`:

  character COLUMN_DESCRIPTION

- `activity_status_code`:

  double COLUMN_DESCRIPTION

- `activity_date_1`:

  date COLUMN_DESCRIPTION

- `activity_date_type_1`:

  double COLUMN_DESCRIPTION

- `activity_date_2`:

  date COLUMN_DESCRIPTION

- `activity_date_type_2`:

  double COLUMN_DESCRIPTION

- `activity_date_3`:

  date COLUMN_DESCRIPTION

- `activity_date_type_3`:

  double COLUMN_DESCRIPTION

- `activity_date_4`:

  date COLUMN_DESCRIPTION

- `activity_date_type_4`:

  double COLUMN_DESCRIPTION

- `contact_info_type`:

  character COLUMN_DESCRIPTION

- `contact_info_org`:

  character COLUMN_DESCRIPTION

- `contact_info_email`:

  character COLUMN_DESCRIPTION

- `contact_info_website`:

  character COLUMN_DESCRIPTION

- `contact_info_mailing_address`:

  character COLUMN_DESCRIPTION

- `activity_scope_code`:

  double activity_scope_code

- `recipient_country_code`:

  character recipient_country_code alpha 2 letters

- `recipient_country_pct`:

  logical percentage of this activity to the recipoent country

- `recipient_country`:

  logical COLUMN_DESCRIPTION

- `recipient_region_code`:

  double COLUMN_DESCRIPTION

- `recipient_region_vocabulary`:

  double COLUMN_DESCRIPTION

- `recipient_region_vocabulary_url`:

  character COLUMN_DESCRIPTION

- `recipient_region_pct`:

  logical COLUMN_DESCRIPTION

- `recipient_region`:

  character recipient_region

- `collaboration_type_code`:

  double The type of collaboration involved in the activity’s
  disbursements, e.g. “bilateral” or “multilateral”.

- `default_flow_type_code`:

  double COLUMN_DESCRIPTION

- `default_finance_type_code`:

  double COLUMN_DESCRIPTION

- `default_tied_status_code`:

  double COLUMN_DESCRIPTION

- `capital_spend`:

  double capital_spend

- `year`:

  character iati id year

- `iati_identifier_reg_ops`:

  character iati_identifier_reg_ops

- `is_operation`:

  logical is a UNHCR Field Operation

- `programmme`:

  character ID of the programme or region

- `programmme_lab`:

  character label of the programme or region

- `iati_identifier_ops`:

  character Operation identifier

- `iso3c`:

  character iso 3 character for the country

- `ops_type`:

  character type of operation if not single country operation

- `ctr_name`:

  character countyr name

- `unhcr_region`:

  character unhcr region

- `reporting_org_type_name`:

  character reporting_org_type_name

- `reporting_org_type_description`:

  character reporting_org_type_description

- `activity_status_name`:

  character activity_status_name

- `activity_status_description`:

  character activity_status_description

- `activity_scope_name`:

  character activity_scope_name

- `activity_scope_description`:

  character activity_scope_description

- `collaboration_type_name`:

  character collaboration_type_name

- `collaboration_type_description`:

  character collaboration_type_description

## Source

<https://iatistandard.org/en/iati-standard/203/activity-standard/iati-activities/iati-activity/>

## Examples

``` r
{
knitr::kable(head(dataActivity, 10))
}
#> 
#> 
#> |iati_identifier              |reporting_org                                         |reporting_org_ref | reporting_org_type|reporting_org_secondary_reporter |title_eng                                                              |title_fr                                                                 | description_type_1|description_eng_1                                                                                                                                                                                                                                     |description_fr_1                                                                                                                                                                                                                                                                | description_type_2|description_eng_2                                                                                                                                                                                   |description_fr_2                                                                                                                                                                                                                                                        | activity_status_code|activity_date_1 | activity_date_type_1|activity_date_2 | activity_date_type_2|activity_date_3 | activity_date_type_3|activity_date_4 | activity_date_type_4|contact_info_type |contact_info_org                                      |contact_info_email |contact_info_website  | activity_scope_code|recipient_country_code |recipient_country_pct |recipient_country | recipient_region_code| recipient_region_vocabulary|recipient_region             | collaboration_type_code| default_flow_type_code| default_finance_type_code| default_tied_status_code| capital_spend| year|iati_identifier_reg_ops |is_operation |programmme |programmme_lab               |iati_identifier_ops |iso3c |ops_type |ctr_name  |unhcr_region                 |unhcr_region2                |activity_name                           |reporting_org_type_name |reporting_org_type_description |activity_status_name |activity_status_description                                                                                                            |activity_scope_name |activity_scope_description                                                   |collaboration_type_name |collaboration_type_description |
#> |:----------------------------|:-----------------------------------------------------|:-----------------|------------------:|:--------------------------------|:----------------------------------------------------------------------|:------------------------------------------------------------------------|------------------:|:-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------:|:---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------:|:---------------|--------------------:|:---------------|--------------------:|:---------------|--------------------:|:---------------|--------------------:|:-----------------|:-----------------------------------------------------|:------------------|:---------------------|-------------------:|:----------------------|:---------------------|:-----------------|---------------------:|---------------------------:|:----------------------------|-----------------------:|----------------------:|-------------------------:|------------------------:|-------------:|----:|:-----------------------|:------------|:----------|:----------------------------|:-------------------|:-----|:--------|:---------|:----------------------------|:----------------------------|:---------------------------------------|:-----------------------|:------------------------------|:--------------------|:--------------------------------------------------------------------------------------------------------------------------------------|:-------------------|:----------------------------------------------------------------------------|:-----------------------|:------------------------------|
#> |XM-DAC-41121-2022            |United Nations High Commissioner for Refugees (UNHCR) |XM-DAC-41121      |                 40|NA                               |UNHCR - The UN Refugee Agency (2022)                                   |UNHCR - L'Agence des Nations Unies pour les réfugiés (2022)              |                  1|This is the overall activity for 2022 UNHCR operations.                                                                                                                                                                                               |Celle-ci est l'activité globale des opérations du HCR en 2022.                                                                                                                                                                                                                  |                  3|UNHCR, the UN Refugee Agency, is a global organisation dedicated to saving lives, protecting rights and building a better future for refugees, forcibly displaced communities and stateless people. |Le HCR, l'Agence des Nations Unies pour les réfugiés, est une organisation internationale qui a pour mission de sauver des vies, de protéger les droits des réfugiés et de construire un avenir meilleur pour les réfugiés, les communautés déplacées et les apatrides. |                    3|2022-12-31      |                    4|2022-12-31      |                    3|2022-01-01      |                    1|2022-01-01      |                    2|1                 |United Nations High Commissioner for Refugees (UNHCR) |IATI@unhcr.org     |http://www.unhcr.org/ |                   1|NA                     |NA                    |NA                |                   998|                           1|Global                       |                       4|                     10|                       110|                        5|             0| 2022|                        |FALSE        |           |                             |                    |      |         |NA        |Global                       |Global                       |Global                                  |Multilateral            |NA                             |Finalisation         |Physical activity is complete or the final disbursement has been made, but the activity remains open pending financial sign off or M&E |Global              |The activity scope is global                                                 |Multilateral outflows   |NA                             |
#> |XM-DAC-41121-2022-AME        |United Nations High Commissioner for Refugees (UNHCR) |XM-DAC-41121      |                 40|NA                               |UNHCR operations in the Americas (2022)                                |Opérations du HCR dans les Amériques (2022)                              |                  1|This activity shows details of the UNHCR operations in the Americas for 2022 including broadly earmarked contributions.                                                                                                                               |Cette activité montre les détails des opérations du HCR dans les Amériques pour 2022, y compris les financements affectés au niveau régional.                                                                                                                                   |                  3|UNHCR, the UN Refugee Agency, is a global organisation dedicated to saving lives, protecting rights and building a better future for refugees, forcibly displaced communities and stateless people. |Le HCR, l'Agence des Nations Unies pour les réfugiés, est une organisation internationale qui a pour mission de sauver des vies, de protéger les droits des réfugiés et de construire un avenir meilleur pour les réfugiés, les communautés déplacées et les apatrides. |                    3|2022-12-31      |                    3|2022-01-01      |                    1|2022-12-31      |                    4|2022-01-01      |                    2|1                 |United Nations High Commissioner for Refugees (UNHCR) |IATI@unhcr.org     |http://www.unhcr.org/ |                   2|NA                     |NA                    |NA                |                   498|                           1|The Americas                 |                       4|                     10|                       110|                        5|             0| 2022|AME                     |FALSE        |AME        |The Americas                 |                    |      |         |NA        |The Americas                 |The Americas                 |Regional - The Americas                 |Multilateral            |NA                             |Finalisation         |Physical activity is complete or the final disbursement has been made, but the activity remains open pending financial sign off or M&E |Regional            |The activity scope is a supranational region                                 |Multilateral outflows   |NA                             |
#> |XM-DAC-41121-2022-ASO        |United Nations High Commissioner for Refugees (UNHCR) |XM-DAC-41121      |                 40|NA                               |UNHCR operations in Asia and the Pacific (2022)                        |Opérations du HCR en Asie et dans le Pacifique (2022)                    |                  1|This activity shows details of the UNHCR operations in Asia and the Pacific for 2022 including broadly earmarked contributions.                                                                                                                       |Cette activité montre les détails des opérations du HCR en Asie et dans le Pacifique pour 2022, y compris les financements affectés au niveau régional.                                                                                                                         |                  3|UNHCR, the UN Refugee Agency, is a global organisation dedicated to saving lives, protecting rights and building a better future for refugees, forcibly displaced communities and stateless people. |Le HCR, l'Agence des Nations Unies pour les réfugiés, est une organisation internationale qui a pour mission de sauver des vies, de protéger les droits des réfugiés et de construire un avenir meilleur pour les réfugiés, les communautés déplacées et les apatrides. |                    3|2022-12-31      |                    4|2022-12-31      |                    3|2022-01-01      |                    1|2022-01-01      |                    2|1                 |United Nations High Commissioner for Refugees (UNHCR) |IATI@unhcr.org     |http://www.unhcr.org/ |                   2|NA                     |NA                    |NA                |                   998|                           1|Asia and the Pacific         |                       4|                     10|                       110|                        5|             0| 2022|ASO                     |FALSE        |ASO        |Asia and the Pacific         |                    |      |         |NA        |Asia and the Pacific         |Asia and the Pacific         |Regional - Asia and the Pacific         |Multilateral            |NA                             |Finalisation         |Physical activity is complete or the final disbursement has been made, but the activity remains open pending financial sign off or M&E |Regional            |The activity scope is a supranational region                                 |Multilateral outflows   |NA                             |
#> |XM-DAC-41121-2022-EHGL       |United Nations High Commissioner for Refugees (UNHCR) |XM-DAC-41121      |                 40|NA                               |UNHCR operations in the East and Horn of Africa and Great Lakes (2022) |Opérations du HCR dans l'Est et Corne de l'Afrique et Grands Lacs (2022) |                  1|This activity shows details of the UNHCR operations in the East, Horn, and Great Lakes of Africa for 2022 including softly earmarked contributions.                                                                                                   |Cette activité montre les détails des opérations du HCR en l'Est, Corne et Grands Lacs d'Afrique pour 2022, y compris les financements affectés au niveau régional.                                                                                                             |                  3|UNHCR, the UN Refugee Agency, is a global organisation dedicated to saving lives, protecting rights and building a better future for refugees, forcibly displaced communities and stateless people. |Le HCR, l'Agence des Nations Unies pour les réfugiés, est une organisation internationale qui a pour mission de sauver des vies, de protéger les droits des réfugiés et de construire un avenir meilleur pour les réfugiés, les communautés déplacées et les apatrides. |                    3|2022-01-01      |                    2|2022-01-01      |                    1|2022-12-31      |                    3|2022-12-31      |                    4|1                 |United Nations High Commissioner for Refugees (UNHCR) |IATI@unhcr.org     |http://www.unhcr.org/ |                   2|NA                     |NA                    |NA                |                   289|                           1|Africa                       |                       4|                     10|                       110|                        5|             0| 2022|EHGL                    |FALSE        |EHGL       |East and Horn of Africa      |                    |      |         |NA        |Africa                       |Africa                       |Regional - Africa                       |Multilateral            |NA                             |Finalisation         |Physical activity is complete or the final disbursement has been made, but the activity remains open pending financial sign off or M&E |Regional            |The activity scope is a supranational region                                 |Multilateral outflows   |NA                             |
#> |XM-DAC-41121-2022-EUR        |United Nations High Commissioner for Refugees (UNHCR) |XM-DAC-41121      |                 40|NA                               |UNHCR operations in Europe (2022)                                      |Opérations du HCR en Europe (2022)                                       |                  1|This activity shows details of the UNHCR operations in Europe for 2022 including including broadly earmarked contributions.                                                                                                                           |Cette activité montre les détails des opérations du HCR en Europe pour 2022, y compris les financements affectés au niveau régional.                                                                                                                                            |                  3|UNHCR, the UN Refugee Agency, is a global organisation dedicated to saving lives, protecting rights and building a better future for refugees, forcibly displaced communities and stateless people. |Le HCR, l'Agence des Nations Unies pour les réfugiés, est une organisation internationale qui a pour mission de sauver des vies, de protéger les droits des réfugiés et de construire un avenir meilleur pour les réfugiés, les communautés déplacées et les apatrides. |                    3|2022-12-31      |                    4|2022-01-01      |                    1|2022-12-31      |                    3|2022-01-01      |                    2|1                 |United Nations High Commissioner for Refugees (UNHCR) |IATI@unhcr.org     |http://www.unhcr.org/ |                   2|NA                     |NA                    |NA                |                    89|                           1|Europe                       |                       4|                     10|                       110|                        5|             0| 2022|EUR                     |FALSE        |EUR        |Europe                       |                    |      |         |NA        |Europe                       |Europe                       |Regional - Europe                       |Multilateral            |NA                             |Finalisation         |Physical activity is complete or the final disbursement has been made, but the activity remains open pending financial sign off or M&E |Regional            |The activity scope is a supranational region                                 |Multilateral outflows   |NA                             |
#> |XM-DAC-41121-2022-MENA       |United Nations High Commissioner for Refugees (UNHCR) |XM-DAC-41121      |                 40|NA                               |UNHCR operations in the Middle East and North Africa (2022)            |Opérations du HCR au Moyen-Orient et au Afrique du Nord (2022)           |                  1|This activity shows details of the UNHCR operations in the Middle East and North Africa for 2022 including broadly earmarked contributions.                                                                                                           |Cette activité montre les détails des opérations du HCR au Moyen-Orient et au Afrique du Nord pour 2022, y compris les financements affectés au niveau régional.                                                                                                                |                  3|UNHCR, the UN Refugee Agency, is a global organisation dedicated to saving lives, protecting rights and building a better future for refugees, forcibly displaced communities and stateless people. |Le HCR, l'Agence des Nations Unies pour les réfugiés, est une organisation internationale qui a pour mission de sauver des vies, de protéger les droits des réfugiés et de construire un avenir meilleur pour les réfugiés, les communautés déplacées et les apatrides. |                    3|2022-12-31      |                    3|2022-12-31      |                    4|2022-01-01      |                    2|2022-01-01      |                    1|1                 |United Nations High Commissioner for Refugees (UNHCR) |IATI@unhcr.org     |http://www.unhcr.org/ |                   2|NA                     |NA                    |NA                |                   998|                           1|Middle East and North Africa |                       4|                     10|                       110|                        5|             0| 2022|MENA                    |FALSE        |MENA       |Middle East and North Africa |                    |      |         |NA        |Middle East and North Africa |Middle East and North Africa |Regional - Middle East and North Africa |Multilateral            |NA                             |Finalisation         |Physical activity is complete or the final disbursement has been made, but the activity remains open pending financial sign off or M&E |Regional            |The activity scope is a supranational region                                 |Multilateral outflows   |NA                             |
#> |XM-DAC-41121-2022-SAO        |United Nations High Commissioner for Refugees (UNHCR) |XM-DAC-41121      |                 40|NA                               |UNHCR operations in Southern Africa (2022)                             |Opérations du HCR en Afrique australe (2022)                             |                  1|This activity shows details of the UNHCR operations in Southern Africa for 2022 including broadly earmarked contributions.                                                                                                                            |Cette activité montre les détails des opérations du HCR à l'Afrique australe pour 2022, y compris les financements affectés au niveau régional.                                                                                                                                 |                  3|UNHCR, the UN Refugee Agency, is a global organisation dedicated to saving lives, protecting rights and building a better future for refugees, forcibly displaced communities and stateless people. |Le HCR, l'Agence des Nations Unies pour les réfugiés, est une organisation internationale qui a pour mission de sauver des vies, de protéger les droits des réfugiés et de construire un avenir meilleur pour les réfugiés, les communautés déplacées et les apatrides. |                    3|2022-01-01      |                    1|2022-12-31      |                    3|2022-12-31      |                    4|2022-01-01      |                    2|1                 |United Nations High Commissioner for Refugees (UNHCR) |IATI@unhcr.org     |http://www.unhcr.org/ |                   2|NA                     |NA                    |NA                |                   289|                           1|Africa                       |                       4|                     10|                       110|                        5|             0| 2022|SAO                     |FALSE        |SAO        |Southern Africa              |                    |      |         |NA        |Africa                       |Africa                       |Regional - Africa                       |Multilateral            |NA                             |Finalisation         |Physical activity is complete or the final disbursement has been made, but the activity remains open pending financial sign off or M&E |Regional            |The activity scope is a supranational region                                 |Multilateral outflows   |NA                             |
#> |XM-DAC-41121-2022-WCA        |United Nations High Commissioner for Refugees (UNHCR) |XM-DAC-41121      |                 40|NA                               |UNHCR operations in West and Central Africa (2022)                     |Opérations du HCR en Afrique occidentale et centrale (2022)              |                  1|This activity shows details of the UNHCR operations in the West and Centre of Africa for 2022 including broadly earmarked contributions.                                                                                                              |Cette activité montre les détails des opérations du HCR à l'Afrique de l'Ouest et L'Afrique centrale pour 2022, y compris les financements affectés au niveau régional.                                                                                                         |                  3|UNHCR, the UN Refugee Agency, is a global organisation dedicated to saving lives, protecting rights and building a better future for refugees, forcibly displaced communities and stateless people. |Le HCR, l'Agence des Nations Unies pour les réfugiés, est une organisation internationale qui a pour mission de sauver des vies, de protéger les droits des réfugiés et de construire un avenir meilleur pour les réfugiés, les communautés déplacées et les apatrides. |                    3|2022-01-01      |                    2|2022-12-31      |                    3|2022-12-31      |                    4|2022-01-01      |                    1|1                 |United Nations High Commissioner for Refugees (UNHCR) |IATI@unhcr.org     |http://www.unhcr.org/ |                   2|NA                     |NA                    |NA                |                   289|                           1|Africa                       |                       4|                     10|                       110|                        5|             0| 2022|WCA                     |FALSE        |WCA        |West and Central Africa      |                    |      |         |NA        |Africa                       |Africa                       |Regional - Africa                       |Multilateral            |NA                             |Finalisation         |Physical activity is complete or the final disbursement has been made, but the activity remains open pending financial sign off or M&E |Regional            |The activity scope is a supranational region                                 |Multilateral outflows   |NA                             |
#> |XM-DAC-41121-2022-AME-ARGMCO |United Nations High Commissioner for Refugees (UNHCR) |XM-DAC-41121      |                 40|NA                               |UNHCR Argentina Multi-Country Office (2022)                            |Bureau multipays du HCR en Argentine (2022)                              |                  1|This activity shows details of the UNHCR Argentina Multi-Country Office for 2022 including the budget, funding, expenditure and results. The Argentina Multi-Country Office coordinates activities in Argentina, Bolivia, Chile, Paraguay and Uruguay |Cette activité montre les détails de Argentine bureau multipays du HCR pour 2022, y compris le budget, les financements, les dépenses et les résultats.  Le bureau multipays d'Argentine coordonne les activités en Argentine, en Bolivie, au Chili, au Paraguay et en Uruguay. |                  3|UNHCR, the UN Refugee Agency, is a global organisation dedicated to saving lives, protecting rights and building a better future for refugees, forcibly displaced communities and stateless people. |Le HCR, l'Agence des Nations Unies pour les réfugiés, est une organisation internationale qui a pour mission de sauver des vies, de protéger les droits des réfugiés et de construire un avenir meilleur pour les réfugiés, les communautés déplacées et les apatrides. |                    3|2022-01-01      |                    2|2022-12-31      |                    3|2022-12-31      |                    4|2022-01-01      |                    1|1                 |United Nations High Commissioner for Refugees (UNHCR) |IATI@unhcr.org     |http://www.unhcr.org/ |                   3|AR                     |NA                    |NA                |                    NA|                          NA|NA                           |                       4|                     10|                       110|                        5|             0| 2022|AME-ARGMCO              |TRUE         |AME        |The Americas                 |ARGMCO              |ARG   |MCO      |Argentina |The Americas                 |The Americas                 |Argentina - MCO                         |Multilateral            |NA                             |Finalisation         |Physical activity is complete or the final disbursement has been made, but the activity remains open pending financial sign off or M&E |Multi-national      |The activity scope covers multiple countries, that don't constitute a region |Multilateral outflows   |NA                             |
#> |XM-DAC-41121-2022-AME-BRA    |United Nations High Commissioner for Refugees (UNHCR) |XM-DAC-41121      |                 40|NA                               |UNHCR operation in Brazil (2022)                                       |L'opération du HCR au Brésil (2022)                                      |                  1|This activity shows details of the UNHCR operation in Brazil for 2022 including the budget, funding, expenditure and results.                                                                                                                         |Cette activité montre les détails de l'opération du HCR au Brésil pour 2022, y compris le budget, les financements, les dépenses et les résultats.                                                                                                                              |                  3|UNHCR, the UN Refugee Agency, is a global organisation dedicated to saving lives, protecting rights and building a better future for refugees, forcibly displaced communities and stateless people. |Le HCR, l'Agence des Nations Unies pour les réfugiés, est une organisation internationale qui a pour mission de sauver des vies, de protéger les droits des réfugiés et de construire un avenir meilleur pour les réfugiés, les communautés déplacées et les apatrides. |                    3|2022-12-31      |                    3|2022-01-01      |                    2|2022-12-31      |                    4|2022-01-01      |                    1|1                 |United Nations High Commissioner for Refugees (UNHCR) |IATI@unhcr.org     |http://www.unhcr.org/ |                   4|BR                     |NA                    |NA                |                    NA|                          NA|NA                           |                       4|                     10|                       110|                        5|             0| 2022|AME-BRA                 |TRUE         |AME        |The Americas                 |BRA                 |BRA   |         |Brazil    |The Americas                 |The Americas                 |Brazil                                  |Multilateral            |NA                             |Finalisation         |Physical activity is complete or the final disbursement has been made, but the activity remains open pending financial sign off or M&E |National            |The activity scope covers one country                                        |Multilateral outflows   |NA                             |
```
