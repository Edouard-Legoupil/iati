# Donor ranking by funding volume (lollipop) with optional WB population/GDP weighting

See original docs above. In single-year earmarking mode, this version
computes: - Total USD, Unearmarked USD, USD/GDP - Scales each to a 0–100
score across donors (min–max) - Computes ranks (best=1) per metric -
Plots x=metric type, y=score; all donors grey, highlighted donor blue
with rank labels.

## Usage

``` r
show_donor_ranking(
  donor_name = NULL,
  top_n_display = 10,
  year = NULL,
  ctr_name = NULL,
  weight_by = c("none", "population", "gdp", "population_gdp"),
  donor_country_map = NULL,
  wb_lang = "en",
  top_n_earmarking = 8,
  verbose = TRUE
)
```

## Examples

``` r
# Example usage:
show_donor_ranking(  
   year = 2025,
   top_n_display = 20 )
#> Single-year earmarking scoring built for year: 2025
#> Donors included: 126
#> USD/GDP available for 0 donors (126 without GDP).
#> Tip: pass donor_name = '...' to highlight a donor in blue.


show_donor_ranking(
  donor_name = "Private donors",
  year = c(2023,2024,2025),
  top_n_display = 10
)


show_donor_ranking(   
  donor_name = "Private donors", 
   year = 2023,
   top_n_display = 10 )
#> Single-year earmarking scoring built for year: 2023
#> Donors included: 134
#> USD/GDP available for 0 donors (134 without GDP).


```
