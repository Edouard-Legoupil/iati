# -- Donor Analysis

``` r
library(iati)
#> Warning: replacing previous import 'cowplot::align_plots' by
#> 'patchwork::align_plots' when loading 'iati'
#> Warning: replacing previous import 'purrr::flatten_lgl' by 'rlang::flatten_lgl'
#> when loading 'iati'
#> Warning: replacing previous import 'purrr::splice' by 'rlang::splice' when
#> loading 'iati'
#> Warning: replacing previous import 'purrr::flatten_chr' by 'rlang::flatten_chr'
#> when loading 'iati'
#> Warning: replacing previous import 'purrr::flatten_raw' by 'rlang::flatten_raw'
#> when loading 'iati'
#> Warning: replacing previous import 'purrr::flatten' by 'rlang::flatten' when
#> loading 'iati'
#> Warning: replacing previous import 'purrr::flatten_dbl' by 'rlang::flatten_dbl'
#> when loading 'iati'
#> Warning: replacing previous import 'purrr::invoke' by 'rlang::invoke' when
#> loading 'iati'
#> Warning: replacing previous import 'purrr::flatten_int' by 'rlang::flatten_int'
#> when loading 'iati'
#> Warning: replacing previous import 'purrr::discard' by 'scales::discard' when
#> loading 'iati'
#> Warning: replacing previous import 'dplyr::lag' by 'stats::lag' when loading
#> 'iati'
#> Warning: replacing previous import 'dplyr::filter' by 'stats::filter' when
#> loading 'iati'
#> Warning: replacing previous import 'rlang::as_list' by 'xml2::as_list' when
#> loading 'iati'
#> Warning: replacing previous import 'stats::filter' by 'dplyr::filter' when
#> loading 'iati'
```

## show_donor_ranking

``` r
# Example usage:
show_donor_ranking(  
   year = 2025,
   top_n_display = 20 )
```

![](donor-analysis_files/figure-html/example-show_donor_ranking-1.png)

``` r

show_donor_ranking(
  donor_name = "Private donors",
  year = c(2023,2024,2025),
  top_n_display = 10
)
```

![](donor-analysis_files/figure-html/example-show_donor_ranking-2.png)

``` r

show_donor_ranking(   
  donor_name = "Private donors", 
   year = 2023,
   top_n_display = 10 )
```

![](donor-analysis_files/figure-html/example-show_donor_ranking-3.png)

## show_donor_funding_over_time

``` r
show_donor_funding_over_time(donor_name = "Private donors",
                                         year = c(2022, 2023, 20234, 2025),
                                         by = "global" )
```

![](donor-analysis_files/figure-html/example-show_donor_funding_over_time-1.png)

``` r
show_donor_funding_over_time(donor_name = "Private donors",
                                         year = c(2022, 2023, 20234, 2025),
                                         by = "region" )
```

![](donor-analysis_files/figure-html/example-show_donor_funding_over_time-2.png)

``` r
show_donor_funding_over_time(donor_name = "Private donors",
                                         year = c(2022, 2023, 20234, 2025),
                                         by = "earmarking_name" )
```

![](donor-analysis_files/figure-html/example-show_donor_funding_over_time-3.png)

``` r
show_donor_funding_over_time(donor_name = "Private donors",
                                         year = c(2022, 2023, 20234, 2025),
                                         by = "country",
                                         top_n_countries = 10)
```

![](donor-analysis_files/figure-html/example-show_donor_funding_over_time-4.png)

## show_donor_earmarking

``` r
show_donor_earmarking(donor_name = "Private donors",
                                         year = c(2022, 2023, 2024, 2025),
                                         by = "global") 
```

![](donor-analysis_files/figure-html/example-show_donor_earmarking-1.png)

``` r
show_donor_earmarking(donor_name = "Private donors",
                                         year = c(2022, 2023, 2024, 2025),
                                         by = "date") 
```

![](donor-analysis_files/figure-html/example-show_donor_earmarking-2.png)

``` r
show_donor_earmarking(donor_name = "Private donors",
                                         year = c(  2025),
                                         by = "region") 
```

![](donor-analysis_files/figure-html/example-show_donor_earmarking-3.png)

## show_donor_earmarking_flexibility_over_time

``` r
# Earmarking Flexibility Over Time
show_donor_earmarking_flexibility_over_time(donor_name = "Private donors",
                                            ctr_name = "Syria")
```

![](donor-analysis_files/figure-html/example-show_donor_earmarking_flexibility_over_time-1.png)

## show_donor_transaction_desc

``` r

# Show top 10 transaction descriptions for a donor
show_donor_transaction_desc(
  donor_name = "Private donors", 
  year = 2024,
  top_n = 10
)
```

![](donor-analysis_files/figure-html/example-show_donor_transaction_desc-1.png)

``` r

# Show top 10 transaction descriptions for a donor
show_donor_transaction_desc(
  donor_name = "Private donors", 
  year = 2022:2025,
  top_n = 10
)
```

![](donor-analysis_files/figure-html/example-show_donor_transaction_desc-2.png)

``` r

# Show earmarking breakdown with proper color coding
show_donor_transaction_desc(
  donor_name = "Private donors",
  by = "earmarking_name",
  year = 2024,
  top_n = 4  # Shows all 4 earmarking types
)
```

![](donor-analysis_files/figure-html/example-show_donor_transaction_desc-3.png)

``` r

# Show funding by region
show_donor_transaction_desc(
  donor_name = "Private donors",
  by = "unhcr_region",
  year = 2025,
  top_n = 8
)
```

![](donor-analysis_files/figure-html/example-show_donor_transaction_desc-4.png)

## compare_donor_profiles

``` r
# Compare Donor Profiles

## using mean
compare_donor_profiles(
  donor_names = "Private donors",
  by = "earmarking",
  year = 2025,
  avg_method = "mean_of_donors",
  display_mode = "absolute"
)
```

![](donor-analysis_files/figure-html/example-compare_donor_profiles-1.png)

``` r
compare_donor_profiles(
  donor_names = "Private donors",
  by = "earmarking",
  year = 2025,
  avg_method = "mean_of_donors",
  display_mode = "relative"
)
```

![](donor-analysis_files/figure-html/example-compare_donor_profiles-2.png)

``` r

## using pooled
compare_donor_profiles(
  donor_names = "Private donors",
  by = "earmarking",
  year = 2025,
  avg_method = "pooled",
  display_mode = "absolute"
)
```

![](donor-analysis_files/figure-html/example-compare_donor_profiles-3.png)

``` r


compare_donor_profiles(
  donor_names = "Private donors",
  by = "earmarking",
  year = 2025,
  avg_method = "pooled",
  display_mode = "relative"
)
```

![](donor-analysis_files/figure-html/example-compare_donor_profiles-4.png)

``` r


compare_donor_profiles(
  donor_names = "Private donors",
  by = "region",
  year = 2025,
  avg_method = "pooled",
  display_mode = "relative"
)
```

![](donor-analysis_files/figure-html/example-compare_donor_profiles-5.png)

``` r

compare_donor_profiles(
  donor_names = c("Private donors", 
 "Switzerland - Swiss Agency for Development and Cooperation (SDC)"), 
   by = "earmarking", 
 year = 2025, 
 ctr_name = "Brazil")
```

![](donor-analysis_files/figure-html/example-compare_donor_profiles-6.png)

## show_donor_geographic_priority_shift

``` r
# Example usage: 
show_donor_geographic_priority_shift(
   donor_name = "Private donors", 
   top_n_countries = 7,
   start_year = 2022,
   end_year = 2025
 )
```

![](donor-analysis_files/figure-html/example-show_donor_geographic_priority_shift-1.png)

## show_donor_activity_diversification

``` r
# Example usage:
show_donor_activity_diversification( 
  donor_name = "Private donors", 
   start_year = 2022, 
   end_year = 2025
)
```

![](donor-analysis_files/figure-html/example-show_donor_activity_diversification-1.png)

## show_donor_funding_volatility

``` r
# Donor Funding Volatility

show_donor_funding_volatility(
  donor_name = "Private donors",
  time_unit = "quarter",
  forecast_horizon = 8
)
```

![](donor-analysis_files/figure-html/example-show_donor_funding_volatility-1.png)

``` r

show_donor_funding_volatility(
  donor_name = "Private donors",
  year = 2022:2026,
  top_n_donors = 10,,
  forecast_horizon = 8,
  time_unit = "month"
)
```

![](donor-analysis_files/figure-html/example-show_donor_funding_volatility-2.png)

``` r

show_donor_funding_volatility(donor_name = "Private donors", 
                              ctr_name = "Brazil")
```

![](donor-analysis_files/figure-html/example-show_donor_funding_volatility-3.png)

## plot_donor_regional_focus_treemap

``` r
# Example usage:
plot_donor_regional_focus_treemap(
  donor_name = "Private donors",
  year = c(2023, 2024, 2025),
  label_font_size = 3
)
```

![](donor-analysis_files/figure-html/example-plot_donor_regional_focus_treemap-1.png)

``` r

plot_donor_regional_focus_treemap(
  donor_name = "Private donors",
  year = 2025,
  label_font_size = 5
)
```

![](donor-analysis_files/figure-html/example-plot_donor_regional_focus_treemap-2.png)

## plot_donor_location_map

``` r
# Example usage:
plot_donor_location_map(
  donor_name = "Private donors",
  year = 2025,
  top_n_locations = 5,
  max_symbol_size = 20
)
```

![](donor-analysis_files/figure-html/example-plot_donor_location_map-1.png)
