# Plot donor activity diversification over time (percentage coverage vs. benchmark lines: Top 5 with donor points, per-year labels (number of operations), and LOESS smoothing

Shows the \*\* Adds three benchmark lines: the \*\*average\*\* coverage
(per year) for donors ranked by annual funding in the \*\*Top 5 The
donor’s path uses \*\*geom_smooth(method = "loess", se = FALSE)\*\*
instead of a straight line, with \*\*points\*\* and \*\*\`ggrepel\`
labels\*\* (absolute \# of countries) for the donor only.

## Usage

``` r
show_donor_activity_diversification(
  donor_name,
  start_year = NULL,
  end_year = NULL,
  loess_span = 0.6,
  verbose = TRUE
)
```

## Arguments

- donor_name:

  Character. Donor to highlight (\`transaction_provider_org\`).

- start_year:

  Optional integer. Inclusive lower bound on year.

- end_year:

  Optional integer. Inclusive upper bound on year.

- loess_span:

  Numeric (0–1+). LOESS span for donor smoothing (default 0.6).

- verbose:

  Logical. Print diagnostics (default TRUE).

## Value

A ggplot object.

## Examples

``` r
# Example usage:
show_donor_activity_diversification( 
  donor_name = "Private donors", 
   start_year = 2022, 
   end_year = 2025
)
#> Years covered: 2022–2025
#> Distinct donors in period: 206
#> Distinct countries per year (min–max): 93–100
#> `geom_smooth()` using formula = 'y ~ x'
#> Warning: span too small.   fewer data values than degrees of freedom.
#> Warning: pseudoinverse used at 2022
#> Warning: neighborhood radius 1.015
#> Warning: reciprocal condition number  0
#> Warning: There are other near singularities as well. 1.0302
#> Warning: span too small.   fewer data values than degrees of freedom.
#> Warning: pseudoinverse used at 2022
#> Warning: neighborhood radius 1.015
#> Warning: reciprocal condition number  0
#> Warning: There are other near singularities as well. 1.0302
#> Warning: span too small.   fewer data values than degrees of freedom.
#> Warning: pseudoinverse used at 2022
#> Warning: neighborhood radius 1.015
#> Warning: reciprocal condition number  0
#> Warning: There are other near singularities as well. 1.0302
#> `geom_smooth()` using formula = 'y ~ x'
#> Warning: span too small.   fewer data values than degrees of freedom.
#> Warning: pseudoinverse used at 2022
#> Warning: neighborhood radius 1.015
#> Warning: reciprocal condition number  0
#> Warning: There are other near singularities as well. 1.0302



```
