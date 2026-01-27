# codeHumCluster

Global Coordination Groups - Cluster & Area of Interest Official Names
and Codes (Beta) Contains IASC designated Global Clusters and Areas of
Responsibility. Global Clusters and Areas of Responsibility (AoR) were
defined to enable more predictable leadership in situations of
humanitarian emergency. The content includes the Preferred Term to be
used for each Cluster and AoR, the Acronym (3-letter cluster code), the
Group to which the term belongs (defining whether it is a Global Cluster
or AoR) and the website URL. Both the Google Spreadsheet and CSV
versions contain HXL hashtags. For more information, please visit
http://vocabulary.unocha.org/

## Usage

``` r
codeHumCluster
```

## Format

A data frame with 16 rows and 9 variables:

- `HRinfo ID`:

  character COLUMN_DESCRIPTION

- `Preferred Term`:

  character COLUMN_DESCRIPTION

- `Preferred Term (fr)`:

  character COLUMN_DESCRIPTION

- `ACRONYM`:

  character COLUMN_DESCRIPTION

- `Group Type`:

  character COLUMN_DESCRIPTION

- `Homepage`:

  character COLUMN_DESCRIPTION

- `Date Created (Post Date)`:

  character COLUMN_DESCRIPTION

- `Updated date`:

  character COLUMN_DESCRIPTION

- `Notes`:

  character COLUMN_DESCRIPTION

## Source

<https://iatistandard.org/en/iati-standard/203/codelists/>

## Examples

``` r
{
knitr::kable(head(codeHumCluster, 10))
}
#> 
#> 
#> |HRinfo ID                      |Preferred Term                 |Preferred Term (fr)               |ACRONYM                |Group Type                           |Homepage                                                                           |Date Created (Post Date) |Updated date   |Notes                                                           |
#> |:------------------------------|:------------------------------|:---------------------------------|:----------------------|:------------------------------------|:----------------------------------------------------------------------------------|:------------------------|:--------------|:---------------------------------------------------------------|
#> |#sector +code +v_hrinfo_sector |#sector +name +preferred +i_en |#sector +name +preferred +i_fr    |#sector +code +acronym |#sector +type                        |#meta +url                                                                         |#date +created           |#date +updated |#meta +comment                                                  |
#> |4                              |Emergency Shelter and NFI      |Abris d'urgence et NFI            |SHL                    |Cluster                              |https://www.sheltercluster.org/                                                    |03/16/2017               |4/4/2018       |Added French name; shelter cluster uses "NFI" in French as well |
#> |1                              |Camp Coordination / Management |Coordination et gestion des camps |CCM                    |Cluster                              |http://www.globalcccmcluster.org                                                   |03/16/2017               |4/4/2018       |Added French name                                               |
#> |5406                           |Mine Action                    |Action contre les mines           |PRO-MIN                |Area of Responsibility (Sub-cluster) |http://www.globalprotectioncluster.org/en/areas-of-responsibility/mine-action.html |03/16/2017               |4/4/2018       |Added French name                                               |
#> |6                              |Food Security                  |Sécurité alimentaire              |FSC                    |Cluster                              |http://foodsecuritycluster.net/                                                    |03/16/2017               |4/4/2018       |Added French name                                               |
#> |11                             |Water Sanitation Hygiene       |Eau, assainissement et hygiène    |WSH                    |Cluster                              |http://washcluster.net/                                                            |03/16/2017               |4/4/2018       |Added French name                                               |
#> |8                              |Logistics                      |Logistique                        |LOG                    |Cluster                              |http://www.logcluster.org/                                                         |03/16/2017               |4/4/2018       |Added French name                                               |
#> |5403                           |Child Protection               |Protection de l'enfance           |PRO-CPN                |Area of Responsibility (Sub-cluster) |http://cpwg.net/                                                                   |03/16/2017               |4/5/2018       |Updated French name based feedback from OCHA-FIS                |
#> |10                             |Protection                     |Protection                        |PRO                    |Cluster                              |http://www.globalprotectioncluster.org/                                            |03/16/2017               |4/4/2018       |Added French name                                               |
#> |3                              |Education                      |Education                         |EDU                    |Cluster                              |http://educationcluster.net/                                                       |03/16/2017               |4/4/2018       |Added French name                                               |
```
