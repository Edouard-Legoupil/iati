# show_sectors

What are the most funded sectors per country (Expenditure evolution per
impact /outcome area)?

## Usage

``` r
show_sectors(
  year,
  programme_lab = NULL,
  iati_identifier_ops = NULL,
  ctr_name = NULL,
  sector_vocabulary_name = "Reporting Organisation 2"
)
```

## Arguments

- year:

  A numeric value or a list of value.

- programme_lab:

  A character vector corresponding to the name of the programme.

- iati_identifier_ops:

  A character vector corresponding to the name of the operation.

- ctr_name:

  A character vector corresponding to the name of the country.

- sector_vocabulary_name:

  sector_vocabulary

## Value

a graph

## Examples

``` r
knitr::kable( iati::dataSector |> 
                dplyr::select( sector_vocabulary_name, sector_vocabulary_description) |>
                dplyr::distinct() |>
                dplyr::filter(!(is.na(sector_vocabulary_name))))
#> 
#> 
#> |sector_vocabulary_name                                         |sector_vocabulary_description                                                                                                                             |
#> |:--------------------------------------------------------------|:---------------------------------------------------------------------------------------------------------------------------------------------------------|
#> |OECD DAC CRS Purpose Codes (5 digit)                           |The sector reported corresponds to an OECD DAC CRS 5-digit purpose code                                                                                   |
#> |Humanitarian Global Clusters (Inter-Agency Standing Committee) |The sector reported corresponds to an Inter-Agency Standard Committee Humanitarian Global Cluster code                                                    |
#> |Reporting Organisation                                         |The sector reported corresponds to a sector vocabulary maintained by the reporting organisation for this activity                                         |
#> |Reporting Organisation 2                                       |The sector reported corresponds to a sector vocabulary maintained by the reporting organisation for this activity (if they are referencing more than one) |
show_sectors(
  year =  c(2022, 2023, 20024, 2025), 
  ctr_name = "Brazil",
  sector_vocabulary_name = "Reporting Organisation")

show_sectors(
  year = 2025, 
  ctr_name = "Brazil",
  sector_vocabulary_name = "Reporting Organisation 2")

show_sectors(
  year = c(2022, 2023, 20024, 2025),  
  ctr_name = "Brazil",
  sector_vocabulary_name = "Reporting Organisation 2")

show_sectors(
  year = c(2022, 2023, 20024, 2025), 
  ctr_name = "Brazil",
  sector_vocabulary_name = "Humanitarian Global Clusters (Inter-Agency Standing Committee)")

show_sectors(
  year = c( 2022, 2023, 20024, 2025), 
  ctr_name = "Brazil",
  sector_vocabulary_name = "OECD DAC CRS Purpose Codes (5 digit)")
```
