# show_indicators_time

How much indicators evolve over time?

## Usage

``` r
show_indicators_time(
  year,
  programme_lab = NULL,
  iati_identifier_ops = NULL,
  ctr_name = NULL,
  result_type_name = "Outcome",
  type = "deviation"
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

- result_type_name:

  either "Impact" "Outcome" "Output" - default is "Outcome"

- type:

  "deviation" showing difference between target and actual - or
  "progress" showing difference between baseline and actual

## Value

a graph

## Examples

``` r
show_indicators_time(year = 2025,  
             ctr_name = "Brazil",
              result_type_name = "Outcome",
             type = "deviation"
             )

show_indicators_time(year =  2025, 
             ctr_name = "Brazil",
              result_type_name = "Outcome",
             type = "progress"
             )

show_indicators_time(year =  2025, 
             ctr_name = "Brazil",
              result_type_name = "Outcome",
             type = "gap"
             )

show_indicators_time(year =  2025, 
             ctr_name = "Brazil",
              result_type_name = "Impact",
             type = "deviation"
             )

show_indicators_time(year =  2025, 
             ctr_name = "Brazil",
              result_type_name = "Impact",
             type = "progress"
             )

show_indicators_time(year =  2025,  
             ctr_name = "Brazil",
              result_type_name = "Output",
             type = "deviation"
             )

show_indicators_time(year =  2025, 
             ctr_name = "Brazil",
              result_type_name = "Output",
             type = "progress"
             )
```
