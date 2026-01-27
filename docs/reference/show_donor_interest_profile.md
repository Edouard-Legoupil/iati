# Plot donor interest profile

Creates a visualization showing the breakdown of a donor's funding. If
only \`by_primary\` is provided, it returns a bar chart. If
\`by_secondary\` is also provided, it returns a heatmap
cross-tabulation.

## Usage

``` r
show_donor_interest_profile(
  donor_name,
  by_primary = "transaction_description",
  by_secondary = NULL,
  year = NULL,
  programme_lab = NULL,
  iati_identifier_ops = NULL,
  ctr_name = NULL,
  top_n = 10
)
```

## Arguments

- donor_name:

  Character. The name of the donor to plot.

- by_primary:

  Character. The primary category to group by. One of "unhcr_region" or
  "transaction_description".

- by_secondary:

  Optional character. A second category to create a heatmap. Also one of
  "unhcr_region" or "transaction_description".

- year:

  Optional numeric/integer vector. Year(s) to filter on.

- programme_lab:

  Optional character vector. Filter for programme name.

- iati_identifier_ops:

  Optional character vector. Filter for operation ID.

- ctr_name:

  Optional character vector. Filter for country name.

- top_n:

  Integer. The number of top categories to show in each dimension.

## Value

A ggplot object.

## Examples

``` r
# Donor Interest Profile
show_donor_interest_profile(donor_name = "Private donors", 
                             by_primary = "transaction_description",
                            year = 2025)


show_donor_interest_profile(donor_name = "Private donors", 
                             by_primary = "unhcr_region",
                            year = 2025)



show_donor_interest_profile(donor_name = "Private donors", 
                             by_primary = "transaction_description",
                             by_secondary = "unhcr_region",
                             year = 2025)
```
