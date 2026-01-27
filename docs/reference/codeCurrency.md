# codeCurrency

ISO 4217 Currency used for all transactions and budgets External URL:
http://www.iso.org/iso/home/standards/currency_codes.htm

## Usage

``` r
codeCurrency
```

## Format

A data frame with 174 rows and 6 variables:

- `code`:

  double code

- `name`:

  character name

- `description`:

  character description

- `category`:

  double category

- `url`:

  character url

- `status`:

  character status

## Source

<https://iatistandard.org/en/iati-standard/203/codelists/>

## Examples

``` r
{
knitr::kable(head(codeCurrency, 10))
}
#> 
#> 
#> |code |name                          |description |category |url |status |
#> |:----|:-----------------------------|:-----------|:--------|:---|:------|
#> |AED  |UAE Dirham                    |NA          |NA       |NA  |active |
#> |AFN  |Afghani                       |NA          |NA       |NA  |active |
#> |ALL  |Lek                           |NA          |NA       |NA  |active |
#> |AMD  |Armenian Dram                 |NA          |NA       |NA  |active |
#> |ANG  |Netherlands Antillian Guilder |NA          |NA       |NA  |active |
#> |AOA  |Kwanza                        |NA          |NA       |NA  |active |
#> |ARS  |Argentine Peso                |NA          |NA       |NA  |active |
#> |AUD  |Australian Dollar             |NA          |NA       |NA  |active |
#> |AWG  |Aruban Guilder                |NA          |NA       |NA  |active |
#> |AZN  |Azerbaijanian Manat           |NA          |NA       |NA  |active |
```
