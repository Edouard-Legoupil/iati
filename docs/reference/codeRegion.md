# codeRegion

External URL: http://www.oecd.org/dac/stats/dacandcrscodelists.htm

## Usage

``` r
codeRegion
```

## Format

A data frame with 26 rows and 6 variables:

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
knitr::kable(head(codeRegion, 10))
}
#> 
#> 
#> | code|name                              |description |category |url |status    |
#> |----:|:---------------------------------|:-----------|:--------|:---|:---------|
#> |   88|States Ex-Yugoslavia unspecified  |NA          |NA       |NA  |active    |
#> |   89|Europe, regional                  |NA          |NA       |NA  |active    |
#> |  189|North of Sahara, regional         |NA          |NA       |NA  |active    |
#> |  289|South of Sahara, regional         |NA          |NA       |NA  |active    |
#> |  298|Africa, regional                  |NA          |NA       |NA  |active    |
#> |  380|West Indies, regional             |NA          |NA       |NA  |withdrawn |
#> |  389|North & Central America, regional |NA          |NA       |NA  |active    |
#> |  489|South America, regional           |NA          |NA       |NA  |active    |
#> |  498|America, regional                 |NA          |NA       |NA  |active    |
#> |  589|Middle East, regional             |NA          |NA       |NA  |active    |
```
