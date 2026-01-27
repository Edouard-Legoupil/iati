# show_donors

Who are the main donors by country in terms of transaction?

## Usage

``` r
show_donors(
  year,
  programme_lab = NULL,
  iati_identifier_ops = NULL,
  ctr_name = NULL,
  transaction_type_name = "Incoming Commitment"
)
```

## Arguments

- year:

  year to select starting from 2016 - could be one year or a list

- programme_lab:

  A character vector corresponding to the name of the programme.

- iati_identifier_ops:

  A character vector corresponding to the name of the operation.

- ctr_name:

  A character vector corresponding to the name of the country.

- transaction_type_name:

  Transaction type - default is "Incoming Commitment" , can also be
  "Disbursement", or "Expenditure"

## Value

a graph

## Examples

``` r
knitr::kable(iati::dataTransaction |>
                dplyr::select( transaction_type_name, transaction_type_description) |>
                dplyr::distinct() )
#> 
#> 
#> |transaction_type_name |transaction_type_description                                                                                                                                                                |
#> |:---------------------|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
#> |Incoming Commitment   |A firm, written obligation from a donor or provider to provide a specified amount of funds, under particular terms and conditions, reported by a recipient for this activity.               |
#> |Expenditure           |Outgoing funds that are spent on goods and services for the activity.                                                                                                                       |
#> |Disbursement          |Outgoing funds that are placed at the disposal of a recipient government or organisation, or funds transferred between two separately reported activities.                                  |
#> |Outgoing Commitment   |A firm, written obligation from a donor or provider to provide a specified amount of funds, under particular terms and conditions, for specific purposes, for the benefit of the recipient. |
show_donors(year = 2025,
           programme_lab = "The Americas",
           transaction_type_name = "Incoming Commitment" )

show_donors(year = c(2022, 2023, 20024, 2025),
           ctr_name = "Brazil",
           transaction_type_name = "Incoming Commitment" )

show_donors(year = c(2022, 2023, 20024, 2025),
           programme_lab = "Brazil",
           transaction_type_name = "Disbursement" )

show_donors(year = c(2022, 2023, 20024, 2025),
           programme_lab = "Brazil",
           transaction_type_name = "Expenditure" )
```
