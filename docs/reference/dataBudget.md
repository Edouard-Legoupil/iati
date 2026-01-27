# dataBudget

Display budget by operation

## Usage

``` r
dataBudget
```

## Format

A data frame with 12 variables:

- `iati_identifier`:

  character COLUMN_DESCRIPTION

- `budget_type`:

  double COLUMN_DESCRIPTION

- `budget_status`:

  double COLUMN_DESCRIPTION

- `budget_period_start`:

  character COLUMN_DESCRIPTION

- `budget_period_end`:

  character COLUMN_DESCRIPTION

- `budget_currency`:

  character COLUMN_DESCRIPTION

- `budget_value_date`:

  character COLUMN_DESCRIPTION

- `budget_value`:

  double COLUMN_DESCRIPTION

- `budget_type_name`:

  character COLUMN_DESCRIPTION

- `budget_type_description`:

  character COLUMN_DESCRIPTION

- `budget_status_name`:

  character COLUMN_DESCRIPTION

- `budget_status_description`:

  character COLUMN_DESCRIPTION

## Source

<https://iatistandard.org/en/iati-standard/203/>

## Examples

``` r
{
knitr::kable(head(dataBudget, 10))
}
#> 
#> 
#> |iati_identifier              | budget_type| budget_status|budget_period_start |budget_period_end |budget_currency |budget_value_date | budget_value|budget_type_name |budget_type_description            |budget_status_name |budget_status_description                     |
#> |:----------------------------|-----------:|-------------:|:-------------------|:-----------------|:---------------|:-----------------|------------:|:----------------|:----------------------------------|:------------------|:---------------------------------------------|
#> |XM-DAC-41121-2022-AME-ARGMCO |           2|             2|2022-01-01          |2022-12-31        |USD             |2021-08-30        |     49164002|Revised          |The updated budget for an activity |Committed          |A binding agreement for the described budget. |
#> |XM-DAC-41121-2022-AME-BRA    |           2|             2|2022-01-01          |2022-12-31        |USD             |2021-08-30        |     52473361|Revised          |The updated budget for an activity |Committed          |A binding agreement for the described budget. |
#> |XM-DAC-41121-2022-AME-CAN    |           2|             2|2022-01-01          |2022-12-31        |USD             |2021-08-30        |      2743877|Revised          |The updated budget for an activity |Committed          |A binding agreement for the described budget. |
#> |XM-DAC-41121-2022-AME-COL    |           2|             2|2022-01-01          |2022-12-31        |USD             |2021-08-30        |    122071446|Revised          |The updated budget for an activity |Committed          |A binding agreement for the described budget. |
#> |XM-DAC-41121-2022-AME-CRI    |           2|             2|2022-01-01          |2022-12-31        |USD             |2021-08-30        |     33902019|Revised          |The updated budget for an activity |Committed          |A binding agreement for the described budget. |
#> |XM-DAC-41121-2022-AME-ECU    |           2|             2|2022-01-01          |2022-12-31        |USD             |2021-08-30        |     76108305|Revised          |The updated budget for an activity |Committed          |A binding agreement for the described budget. |
#> |XM-DAC-41121-2022-AME-GTM    |           2|             2|2022-01-01          |2022-12-31        |USD             |2021-08-30        |     42474637|Revised          |The updated budget for an activity |Committed          |A binding agreement for the described budget. |
#> |XM-DAC-41121-2022-AME-HND    |           2|             2|2022-01-01          |2022-12-31        |USD             |2021-08-30        |     28639888|Revised          |The updated budget for an activity |Committed          |A binding agreement for the described budget. |
#> |XM-DAC-41121-2022-AME-MEX    |           2|             2|2022-01-01          |2022-12-31        |USD             |2021-08-30        |     96603414|Revised          |The updated budget for an activity |Committed          |A binding agreement for the described budget. |
#> |XM-DAC-41121-2022-AME-PANMCO |           2|             2|2022-01-01          |2022-12-31        |USD             |2021-08-30        |     54305964|Revised          |The updated budget for an activity |Committed          |A binding agreement for the described budget. |
```
