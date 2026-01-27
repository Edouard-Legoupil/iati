# -- Data Preparation

``` r
library(iati)
#> Warning: replacing previous import 'cowplot::align_plots' by
#> 'patchwork::align_plots' when loading 'iati'
#> Warning: replacing previous import 'purrr::flatten_lgl' by 'rlang::flatten_lgl'
#> when loading 'iati'
#> Warning: replacing previous import 'purrr::splice' by 'rlang::splice' when
#> loading 'iati'
#> Warning: replacing previous import 'purrr::flatten_chr' by 'rlang::flatten_chr'
#> when loading 'iati'
#> Warning: replacing previous import 'purrr::flatten_raw' by 'rlang::flatten_raw'
#> when loading 'iati'
#> Warning: replacing previous import 'purrr::flatten' by 'rlang::flatten' when
#> loading 'iati'
#> Warning: replacing previous import 'purrr::flatten_dbl' by 'rlang::flatten_dbl'
#> when loading 'iati'
#> Warning: replacing previous import 'purrr::invoke' by 'rlang::invoke' when
#> loading 'iati'
#> Warning: replacing previous import 'purrr::flatten_int' by 'rlang::flatten_int'
#> when loading 'iati'
#> Warning: replacing previous import 'purrr::discard' by 'scales::discard' when
#> loading 'iati'
#> Warning: replacing previous import 'dplyr::lag' by 'stats::lag' when loading
#> 'iati'
#> Warning: replacing previous import 'dplyr::filter' by 'stats::filter' when
#> loading 'iati'
#> Warning: replacing previous import 'rlang::as_list' by 'xml2::as_list' when
#> loading 'iati'
#> Warning: replacing previous import 'stats::filter' by 'dplyr::filter' when
#> loading 'iati'
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
