# Title

What’s the breakdown of Earmarking Type (Un-earmarked, Tightly
earmarked, etc.) \\ from Donor Funds by Year? Where possible, UNHCR
prefers to receive unearmarked funds, as this allows the agency greater
flexibility in allocating its resources as new needs emerge during the
course of the year. Should that not be possible, funds can also be
softly earmarked. This could mean funds that can be spent anywhere
within a region or for a particular situation (for example, funds that
have to be spent to assist refugees from Syria, but which can be spent
in any country hosting such refugees). Earmarked funds would be a
contribution that corresponds to a specific country but can be spent on
anything within that operation’s programme. Finally, tightly earmarked
funds are those that specify an activity or a population within a
country’s programme.

UNHCR charges an ISC - Indirect Support Costs - rate of 6.5 This covers
management and administration costs at HQ and programme support costs
incurred at HQ and Regional Bureaux.

## Usage

``` r
show_earmarking(
  year,
  programme_lab = NULL,
  iati_identifier_ops = NULL,
  ctr_name = NULL
)
```

## Arguments

- year:

  A numeric value or a vector of numeric value to filter on year. Note
  that data pre-2022 are using a different set of indicators

- programme_lab:

  A character vector corresponding to the name of the programme.

- iati_identifier_ops:

  A character vector corresponding to the name of the operation.

- ctr_name:

  A character vector corresponding to the name of the country.

## Value

a graph

## Examples

``` r
knitr::kable(iati::dataTransaction |>
                dplyr::select(earmarking_name, earmarking_description)  |>
                dplyr::distinct() |>
                dplyr::filter(!(is.na(earmarking_name))))
#> 
#> 
#> |earmarking_name   |earmarking_description                                |
#> |:-----------------|:-----------------------------------------------------|
#> |Softly Earmarked  |Any or all of the Earmarking Modality codes D,E or F. |
#> |Unearmarked       |Any or all of the Earmarking Modality codes A,B or C. |
#> |Tightly Earmarked |Any or all of the Earmarking Modality codes I,J or K. |
#> |Earmarked         |Any or all of the Earmarking Modality codes G or H.   |
show_earmarking(year = c(2022, 2023, 20024, 2025),  
             ctr_name = "Brazil")
```
