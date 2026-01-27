# Reshape IATI data and write to files

Reshape IATI data and write to files

## Usage

``` r
iati_reshape_all(
  iati_file_url = "https://files.unhcr.org/en/reporting/unhcr-activities-2026.xml",
  folder_name = "data-raw",
  extractors = NULL,
  verbose = TRUE
)
```

## Arguments

- iati_file_url:

  The URL of the IATI XML file.

- folder_name:

  The destination folder for the output Excel files.

- extractors:

  NULL to run all extractors (default), or a character vector of
  extractor names to run only a subset (e.g., c("location") or
  c("transaction","sector")). Valid names: activity, budget,
  default_aid_type, document_link, humanitarian_scope, location,
  participating_org, related_activity, result, sector, transaction,
  policy_marker, tag

- verbose:

  Whether to show detailed logging messages.

## Examples

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
