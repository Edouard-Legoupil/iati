# dataDocument_link

Links to additional documents in relation with the programme

## Usage

``` r
dataDocument_link
```

## Format

A data frame with 4722 rows and 7 variables:

- `iati_identifier`:

  character A globally unique identifier for the activity.

- `document_url`:

  character document_url

- `document_format`:

  character COLUMN_DESCRIPTION

- `document_title`:

  character COLUMN_DESCRIPTION

- `document_category_code`:

  character COLUMN_DESCRIPTION

- `document_language_code`:

  character COLUMN_DESCRIPTION

- `document_date`:

  character COLUMN_DESCRIPTION

## Source

<https://iatistandard.org/en/iati-standard/203/>

## Examples

``` r
{
knitr::kable(head(dataDocument_link, 10))
}
#> 
#> 
#> |iati_identifier   |document_url                                                  |document_format |document_title                                                |document_category_code |document_language_code |document_date |
#> |:-----------------|:-------------------------------------------------------------|:---------------|:-------------------------------------------------------------|:----------------------|:----------------------|:-------------|
#> |XM-DAC-41121-2022 |http://reporting.unhcr.org/operations                         |text/html       |Operation Website                                             |A12                    |en                     |2023-08-21    |
#> |XM-DAC-41121-2022 |https://intranet.unhcr.org/en/about/strategic-directions.html |text/html       |UNHCR Strategic Directions 2022-2026                          |B02                    |en                     |2023-08-21    |
#> |XM-DAC-41121-2022 |http://www.unhcr.org/ar/                                      |text/html       |المفوضية السامية للأمم المتحدة لشؤون اللاجئين                 |B16                    |ar                     |2023-08-21    |
#> |XM-DAC-41121-2022 |https://help.unhcr.org/                                       |text/html       |Information for Refugees, Asylum-seekers and Stateless People |B16                    |en                     |2023-08-21    |
#> |XM-DAC-41121-2022 |https://www.unhcr.org/population-data.html                    |text/html       |Population Data                                               |B16                    |en                     |2023-08-21    |
#> |XM-DAC-41121-2022 |https://www.unhcr.org/figures-at-a-glance.html                |text/html       |UNHCR - Figures at a glance                                   |B16                    |en                     |2023-08-21    |
#> |XM-DAC-41121-2022 |https://www.unhcr.org/                                        |text/html       |UNHCR - The UN Refugee Agency                                 |B16                    |en                     |2023-08-21    |
#> |XM-DAC-41121-2022 |http://reporting.unhcr.org/iati                               |text/html       |UNHCR IATI Overview                                           |B16                    |en                     |2023-08-21    |
#> |XM-DAC-41121-2022 |http://www.unhcr.org/es/                                      |text/html       |ACNUR La Agencia de la ONU para los Refugiados                |B16                    |es                     |2023-08-21    |
#> |XM-DAC-41121-2022 |http://www.unhcr.org/fr/                                      |text/html       |UNHCR L'Agence des Nations Unies pour les réfugiés            |B16                    |fr                     |2023-08-21    |
```
