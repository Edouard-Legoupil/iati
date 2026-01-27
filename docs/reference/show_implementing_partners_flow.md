# Show a flow diagram of implementing partners

This function creates a Sankey diagram to visualize the relationships
between implementing partner roles, their organization types, and their
names.

## Usage

``` r
show_implementing_partners_flow(
  year,
  ctr_name = NULL,
  programme_lab = NULL,
  iati_identifier_ops = NULL,
  top_n = 15
)
```

## Arguments

- year:

  A numeric value for the year.

- ctr_name:

  A character vector for the country name.

- programme_lab:

  A character vector for the programme name.

- iati_identifier_ops:

  A character vector for the operation ID.

- top_n:

  The number of top implementing partners to show.

## Examples

``` r
show_implementing_partners_flow(year = 2025, ctr_name = "Brazil")
#> Warning: attributes are not identical across measure variables; they will be dropped
```
