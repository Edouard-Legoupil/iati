# Generate a summary powerpoint

Generate a summary powerpoint

## Usage

``` r
template_prez(year = 2025, ctr_name, folder = "Prez")
```

## Arguments

- year:

  A numeric value or a vector of numeric value to filter on year. Note
  that data pre-2022 are using a different set of indicators

- ctr_name:

  A character vector corresponding to the name of the country.

- folder:

  folder within your project where to put the generated report. Folder
  will be created if it does not exist

## Value

nothing the file for the report is generated

## Examples

``` r
## generate for one country
# iati::template_prez(year = 2025, 
#                     ctr_name = "Brazil",
#                     folder = "dev/Prez")

# ## Generate for all operation specific region
# reg <- iati::dataActivity |>
#   dplyr::select( unhcr_region) |>
#   dplyr::filter(! is.na(unhcr_region)) |>
#   dplyr::distinct() |>
#   dplyr::pull() 
# 
# thisfolder <- "dev/SMR" 
# 
# for (region in reg) { 
#       cat(paste0( region,   "\n"))
#
#       # region <- "The Americas"   
#       countries <- iati::dataActivity |>
#         dplyr::filter( unhcr_region ==  region) |>
#         dplyr::select(ctr_name) |>
#         dplyr::distinct() |>
#         dplyr::pull() 
#       
#       for ( ctr in countries) {
#         cat(paste0("Generating for ", ctr, "\n"))
#         iati::template_prez(year = 2025,
#                             ctr_name = ctr,
#                             folder =  thisfolder)  
#         }
#     }
```
