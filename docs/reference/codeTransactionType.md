# codeTransactionType

Transaction Type - This is a Core codelist.

## Usage

``` r
codeTransactionType
```

## Format

A data frame with 13 rows and 6 variables:

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
knitr::kable(head(codeTransactionType, 10))
}
#> 
#> 
#> | code|name                |description                                                                                                                                                                                 |category |url |status |
#> |----:|:-------------------|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:--------|:---|:------|
#> |    1|Incoming Funds      |Funds recieved for use on the activity, which can be from an external or internal source.                                                                                                   |NA       |NA  |active |
#> |    2|Outgoing Commitment |A firm, written obligation from a donor or provider to provide a specified amount of funds, under particular terms and conditions, for specific purposes, for the benefit of the recipient. |NA       |NA  |active |
#> |    3|Disbursement        |Outgoing funds that are placed at the disposal of a recipient government or organisation, or funds transferred between two separately reported activities.                                  |NA       |NA  |active |
#> |    4|Expenditure         |Outgoing funds that are spent on goods and services for the activity.                                                                                                                       |NA       |NA  |active |
#> |    5|Interest Payment    |The actual amount of interest paid on a loan or line of credit, including fees.                                                                                                             |NA       |NA  |active |
#> |    6|Loan Repayment      |The actual amount of principal (amortisation) repaid, including any arrears.                                                                                                                |NA       |NA  |active |
#> |    7|Reimbursement       |A type of disbursement that covers funds that have already been spent by the recipient, as agreed in the terms of the grant or loan                                                         |NA       |NA  |active |
#> |    8|Purchase of Equity  |Outgoing funds that are used to purchase equity in a business                                                                                                                               |NA       |NA  |active |
#> |    9|Sale of Equity      |Incoming funds from the sale of equity.                                                                                                                                                     |NA       |NA  |active |
#> |   10|Credit Guarantee    |A commitment made by a funding organisation to underwrite a loan or line of credit entered into by a third party.                                                                           |NA       |NA  |active |
```
