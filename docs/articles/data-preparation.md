# -- Data Preparation

``` r
library(iati)
```

## Logging Helper

## XML extraction Helpers

## Content Extraction Functions

### iati_result

### iati_related_activity

### iati_participating_org

### iati_location

### iati_humanitarian_scope

### iati_document_link

### iati_default_aid_type

### iati_budget

### iati_activity

## Main Reshape orchestrator

This section contains the main user-facing function `iati_reshape_all`.

``` r


#  Run ONLY the 'location' extractor:
# iati_reshape_all(
#   iati_file_url = "https://files.unhcr.org/en/reporting/unhcr-activities-2026.xml",
#   folder_name   = "data-raw/unhcr_2026",
#   extractors    = "location",
#   verbose       = TRUE
# )


#iati_reshape_all(
# iati_file_url = 'https://files.unhcr.org/en/reporting/unhcr-activities-2022.xml' , 
# folder_name = "data-raw/unhcr_2022")

# iati_reshape_all(
# iati_file_url = 'https://files.unhcr.org/en/reporting/unhcr-activities-2023.xml' ,
# folder_name = "data-raw/unhcr_2023")

# iati_reshape_all( 
# iati_file_url = 'https://files.unhcr.org/en/reporting/unhcr-activities-2024.xml',
# folder_name = "data-raw/unhcr_2024")

# iati_reshape_all( 
# iati_file_url = 'https://files.unhcr.org/en/reporting/unhcr-activities-2025.xml',
# folder_name = "data-raw/unhcr_2025")

# iati_reshape_all( 
# iati_file_url = 'https://files.unhcr.org/en/reporting/unhcr-activities-2026.xml',
# folder_name = "data-raw/unhcr_2026")
```
