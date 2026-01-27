# Generate a summary powerpoint

Generate a summary powerpoint

## Usage

``` r
template_compare(year = 2025, folder = "Compare")
```

## Arguments

- year:

  A numeric value or a vector of numeric value to filter on year. Note
  that data pre-2022 are using a different set of indicators

- folder:

  folder within your project where to put the generated report. Folder
  will be created if it does not exist

- ctr_name:

  A character vector corresponding to the name of the country.

## Value

nothing the file for the report is generated

## Examples

``` r
# iati::template_compare(year = 2025, folder = "dev/Result")
```
