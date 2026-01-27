# show_outcome_result

show_outcome_result

## Usage

``` r
show_outcome_result(
  year,
  programme_lab = NULL,
  iati_identifier_ops = NULL,
  ctr_name = NULL,
  outcome
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

- outcome:

  any of: "OA1: Access to Territory, Reg. and Documentation", "OA2:
  Status Determination", "OA3: Protection Policy and Law", "OA4: Sexual
  and Gender-based Violence", "OA5: Child Protection", "OA6: Safety and
  Access to Justice", "OA7: Community Engagement and Women's
  Empowerment", "OA8: Well-Being and Basic Needs", "OA9: Sustainable
  Housing and Settlements", "OA10: Healthy Lives" , "OA11: Education",
  "OA12: Clean Water, Sanitation and Hygiene", "OA13: Self Reliance,
  Economic Inclusion and Livelihoods", "OA14: Voluntary Repatriation and
  Sustainable Reintegration", "OA15: Resettlement and Complementary
  Pathways", "OA16: Local Integration and other Local Solutions"

## Value

a graph

## Examples

``` r
show_outcome_result(year =  c(2022, 2023, 20024, 2025), 
             ctr_name = "Brazil",
             outcome = "OA2: Status Determination")
#> Warning: Removed 2 rows containing missing values or values outside the scale range
#> (`geom_point()`).
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Error in dplyr::left_join(dfRes, df_bud2, by = c("year")): Can't join `x$year` with `y$year` due to incompatible types.
#> ℹ `x$year` is a <factor<68191>>.
#> ℹ `y$year` is a <double>.
show_outcome_result(year =  c(2022, 2023, 20024, 2025), 
             ctr_name = "Brazil",
             outcome = "OA9: Sustainable Housing and Settlements")
#> Warning: Removed 2 rows containing missing values or values outside the scale range
#> (`geom_point()`).
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Error in dplyr::left_join(dfRes, df_bud2, by = c("year")): Can't join `x$year` with `y$year` due to incompatible types.
#> ℹ `x$year` is a <factor<68191>>.
#> ℹ `y$year` is a <double>.
show_outcome_result(year =  c(2022, 2023, 20024, 2025), 
             ctr_name = "Brazil",
             outcome = "OA8: Well-Being and Basic Needs")
#> Warning: Removed 2 rows containing missing values or values outside the scale range
#> (`geom_point()`).
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Error in dplyr::left_join(dfRes, df_bud2, by = c("year")): Can't join `x$year` with `y$year` due to incompatible types.
#> ℹ `x$year` is a <factor<68191>>.
#> ℹ `y$year` is a <double>.
show_outcome_result(year =  c(2022, 2023, 20024, 2025), 
             ctr_name = "Brazil",
             outcome = "OA4: Sexual and Gender-based Violence")
#> Warning: Removed 3 rows containing missing values or values outside the scale range
#> (`geom_point()`).
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Warning: font family 'Lato' not found in PostScript font database
#> Error in dplyr::left_join(dfRes, df_bud2, by = c("year")): Can't join `x$year` with `y$year` due to incompatible types.
#> ℹ `x$year` is a <factor<68191>>.
#> ℹ `y$year` is a <double>.
```
