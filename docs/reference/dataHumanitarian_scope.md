# dataHumanitarian_scope

DATASET_DESCRIPTION

## Usage

``` r
dataHumanitarian_scope
```

## Format

A data frame with 1578 rows and 8 variables:

- `iati_identifier`:

  character A globally unique identifier for the activity.

- `humanitarian_scope_type`:

  character COLUMN_DESCRIPTION

- `humanitarian_scope_vocabulary`:

  character COLUMN_DESCRIPTION

- `humanitarian_scope_vocabulary_uri`:

  character COLUMN_DESCRIPTION

- `humanitarian_scope_code`:

  character COLUMN_DESCRIPTION

- `humanitarian_scope_pct`:

  logical COLUMN_DESCRIPTION

- `humanitarian_scope_desc_eng`:

  character COLUMN_DESCRIPTION

- `humanitarian_scope_desc_fr`:

  character COLUMN_DESCRIPTION

## Source

<https://iatistandard.org/en/iati-standard/203/>

## Examples

``` r
{
knitr::kable(head(dataHumanitarian_scope, 10))
}
#> 
#> 
#> |iati_identifier              |humanitarian_scope_type |humanitarian_scope_vocabulary |humanitarian_scope_vocabulary_uri       |humanitarian_scope_code |humanitarian_scope_desc_eng |humanitarian_scope_desc_fr |
#> |:----------------------------|:-----------------------|:-----------------------------|:---------------------------------------|:-----------------------|:---------------------------|:--------------------------|
#> |XM-DAC-41121-2022            |2                       |99                            |http://reporting.unhcr.org/publications |GLOBAL-APPEAL-2022      |Global Appeal 2022          |Appel global 2022          |
#> |XM-DAC-41121-2022-AME        |2                       |99                            |http://reporting.unhcr.org/publications |GLOBAL-APPEAL-2022      |Global Appeal 2022          |Appel global 2022          |
#> |XM-DAC-41121-2022-ASO        |2                       |99                            |http://reporting.unhcr.org/publications |GLOBAL-APPEAL-2022      |Global Appeal 2022          |Appel global 2022          |
#> |XM-DAC-41121-2022-EHGL       |2                       |99                            |http://reporting.unhcr.org/publications |GLOBAL-APPEAL-2022      |Global Appeal 2022          |Appel global 2022          |
#> |XM-DAC-41121-2022-EUR        |2                       |99                            |http://reporting.unhcr.org/publications |GLOBAL-APPEAL-2022      |Global Appeal 2022          |Appel global 2022          |
#> |XM-DAC-41121-2022-MENA       |2                       |99                            |http://reporting.unhcr.org/publications |GLOBAL-APPEAL-2022      |Global Appeal 2022          |Appel global 2022          |
#> |XM-DAC-41121-2022-SAO        |2                       |99                            |http://reporting.unhcr.org/publications |GLOBAL-APPEAL-2022      |Global Appeal 2022          |Appel global 2022          |
#> |XM-DAC-41121-2022-WCA        |2                       |99                            |http://reporting.unhcr.org/publications |GLOBAL-APPEAL-2022      |Global Appeal 2022          |Appel global 2022          |
#> |XM-DAC-41121-2022-AME-ARGMCO |2                       |99                            |http://reporting.unhcr.org/publications |GLOBAL-APPEAL-2022      |Global Appeal 2022          |Appel global 2022          |
#> |XM-DAC-41121-2022-AME-BRA    |2                       |99                            |http://reporting.unhcr.org/publications |GLOBAL-APPEAL-2022      |Global Appeal 2022          |Appel global 2022          |
```
