# participating_org

An organisation involved with the activity. May be a donor, fund,
agency, etc. Specifying the ref identifier is strongly recommended. May
contain the organisation name as narrative. If the reporting
organisation plays a role in the activity it should be repeated here.
One organisation may play more than one role (eg, funding and
implementing): in such a case each role should be reported and the name
of the organisation repeated.

## Usage

``` r
dataParticipating_org
```

## Format

A data frame

- `iati_identifier`:

  character A globally unique identifier for the activity.

- `participating_org_eng`:

  character COLUMN_DESCRIPTION

- `participating_org_ref`:

  character Machine-readable identification string for the organisation
  issuing the report. Must be in the format
  RegistrationAgency-RegistrationNumber where RegistrationAgency is a
  valid code in the Organisation Registration Agency code list and
  RegistrationNumber is a valid identifier issued by the
  RegistrationAgency. If this is not present then the narrative MUST
  contain the name of the organisation.

- `participating_org_type`:

  double The type of organisation issuing the report. See IATI codelist
  codeOrganisationType for values.

- `participating_org_role`:

  double An IATI code describing the organisation’s role in the activity
  (donor, agency, etc.). see codeOrganisationRole

- `participating_org_activity_id`:

  logical A valid activity identifier published by the participating
  organisation which points to the activity that it has published to
  IATI that describes its role in this activity.

- `participating_org_crs_channel_code`:

  logical Under CRS++ Reporting Directives this code identifies the
  implementing agency. Codes ending in ‘00’ are generic and are similar
  to the OrganisationType code.

- `participating_org_type_name`:

  character COLUMN_DESCRIPTION

- `participating_org_type_description`:

  character COLUMN_DESCRIPTION

- `participating_org_role_name`:

  character COLUMN_DESCRIPTION

- `participating_org_role_description`:

  character COLUMN_DESCRIPTION

## Source

<https://iatistandard.org/en/iati-standard/203/>

## Examples

``` r
{
knitr::kable(head(dataParticipating_org, 10))
}
#> 
#> 
#> |iati_identifier   |participating_org_eng                                |participating_org_ref | participating_org_type| participating_org_role|participating_org_activity_id |participating_org_crs_channel_code |participating_org_type_name |participating_org_type_description |participating_org_role_name |participating_org_role_description                                   |
#> |:-----------------|:----------------------------------------------------|:---------------------|----------------------:|----------------------:|:-----------------------------|:----------------------------------|:---------------------------|:----------------------------------|:---------------------------|:--------------------------------------------------------------------|
#> |XM-DAC-41121-2022 |Government of Chile                                  |NA                    |                     10|                      1|NA                            |NA                                 |Government                  |NA                                 |Funding                     |The government or organisation which provides funds to the activity. |
#> |XM-DAC-41121-2022 |Australia - Department of  Foreign Affairs and Trade |AU-5                  |                     10|                      1|NA                            |NA                                 |Government                  |NA                                 |Funding                     |The government or organisation which provides funds to the activity. |
#> |XM-DAC-41121-2022 |Government of France                                 |NA                    |                     10|                      1|NA                            |NA                                 |Government                  |NA                                 |Funding                     |The government or organisation which provides funds to the activity. |
#> |XM-DAC-41121-2022 |Government of Philippines                            |NA                    |                     10|                      1|NA                            |NA                                 |Government                  |NA                                 |Funding                     |The government or organisation which provides funds to the activity. |
#> |XM-DAC-41121-2022 |Government of Malta                                  |NA                    |                     10|                      1|NA                            |NA                                 |Government                  |NA                                 |Funding                     |The government or organisation which provides funds to the activity. |
#> |XM-DAC-41121-2022 |UK - Foreign, Commonwealth and Development Office    |GB-GOV-1              |                     10|                      1|NA                            |NA                                 |Government                  |NA                                 |Funding                     |The government or organisation which provides funds to the activity. |
#> |XM-DAC-41121-2022 |Government of Uruguay                                |NA                    |                     10|                      1|NA                            |NA                                 |Government                  |NA                                 |Funding                     |The government or organisation which provides funds to the activity. |
#> |XM-DAC-41121-2022 |Government of Türkiye                                |NA                    |                     10|                      1|NA                            |NA                                 |Government                  |NA                                 |Funding                     |The government or organisation which provides funds to the activity. |
#> |XM-DAC-41121-2022 |Government of Bulgaria                               |NA                    |                     10|                      1|NA                            |NA                                 |Government                  |NA                                 |Funding                     |The government or organisation which provides funds to the activity. |
#> |XM-DAC-41121-2022 |Government of Austria                                |NA                    |                     10|                      1|NA                            |NA                                 |Government                  |NA                                 |Funding                     |The government or organisation which provides funds to the activity. |
```
