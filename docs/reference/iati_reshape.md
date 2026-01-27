# iati_reshape

Take anxml file and creates all the decomposed xls file out o it..

## Usage

``` r
iati_reshape(iati_file_url, extractors = NULL, verbose = TRUE)
```

## Arguments

- xml_iati:

  xml_iati

- folder_name:

  folder_name within project

## Examples

``` r
#iati_reshape(
# iati_file_url = 'https://files.unhcr.org/en/reporting/unhcr-activities-2022.xml' , 
# folder_name = "data-raw")

#iati_reshape( iati_file_url = 'https://files.unhcr.org/en/reporting/unhcr-activities-2022.xml' ,   folder_name = "data-raw")
#iati_reshape( iati_file_url = 'https://files.unhcr.org/en/reporting/unhcr-activities-2023.xml' ,   folder_name = "data-raw")
#iati_reshape( iati_file_url = 'https://files.unhcr.org/en/reporting/unhcr-activities-2024.xml' ,   folder_name = "data-raw")
#iati_reshape( iati_file_url = 'https://files.unhcr.org/en/reporting/unhcr-activities-2025.xml' ,   folder_name = "data-raw")
#iati_reshape( iati_file_url = 'https://files.unhcr.org/en/reporting/unhcr-activities-2026.xml' ,   folder_name = "data-raw")
```
