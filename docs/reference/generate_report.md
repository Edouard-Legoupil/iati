# Generate Quarto HTML / PDF Country Factsheets in Batch

This function renders the 'Country_Factsheet' Quarto template for a list
of countries, generating a report file for each.

## Usage

``` r
generate_report(type = "donor", name = NULL, top_n = 20)
```

## Arguments

- type:

  either donor recipient or destination.

- name:

  name of donor recipient or destination if NULL batch process them

- top_n:

  Top number of report to batch process based on total amount

## Value

links to genrated reports.

## Examples

``` r
# linkdonor <- generate_report(type = "donor", top_n = 20)
# dput(linkdonor)
linkdonor <-   c("[Profile Report for donor: United States of America (Government of)](../reports/iatiAnalysis-donor-united-states-of-america-government-of.html)", 
"[Profile Report for donor: Mastercard Foundation](../reports/iatiAnalysis-donor-mastercard-foundation.html)", 
"[Profile Report for donor: Private donors](../reports/iatiAnalysis-donor-private-donors.html)", 
"[Profile Report for donor: European Commission - Humanitarian Aid & Civil Protection](../reports/iatiAnalysis-donor-european-commission-humanitarian-aid-civil-protection.html)", 
"[Profile Report for donor: Denmark - Ministry of Foreign Affairs, Danida](../reports/iatiAnalysis-donor-denmark-ministry-of-foreign-affairs-danida.html)", 
"[Profile Report for donor: European Commission - Service for Foreign Policy Instruments](../reports/iatiAnalysis-donor-european-commission-service-for-foreign-policy-instruments.html)", 
"[Profile Report for donor: European Commission - Neighbourhood and Enlargement Negotiations](../reports/iatiAnalysis-donor-european-commission-neighbourhood-and-enlargement-negotiations.html)", 
"[Profile Report for donor: Norad - Norwegian Agency for Development Cooperation](../reports/iatiAnalysis-donor-norad-norwegian-agency-for-development-cooperation.html)", 
"[Profile Report for donor: Netherlands - Ministry of Foreign Affairs](../reports/iatiAnalysis-donor-netherlands-ministry-of-foreign-affairs.html)", 
"[Profile Report for donor: Germany - Federal Foreign Office](../reports/iatiAnalysis-donor-germany-federal-foreign-office.html)", 
"[Profile Report for donor: Ministry of Foreign Affairs of  Japan](../reports/iatiAnalysis-donor-ministry-of-foreign-affairs-of-japan.html)", 
"[Profile Report for donor: UK - Foreign, Commonwealth and Development Office](../reports/iatiAnalysis-donor-uk-foreign-commonwealth-and-development-office.html)", 
"[Profile Report for donor: Sweden, through Swedish International Development Cooperation Agency (Sida)](../reports/iatiAnalysis-donor-sweden-through-swedish-international-development-cooperation-agency-sida.html)", 
"[Profile Report for donor: Canada - Global Affairs Canada | Affaires mondiales Canada](../reports/iatiAnalysis-donor-canada-global-affairs-canada-affaires-mondiales-canada.html)", 
"[Profile Report for donor: Switzerland - Swiss Agency for Development and Cooperation (SDC)](../reports/iatiAnalysis-donor-switzerland-swiss-agency-for-development-and-cooperation-sdc.html)", 
"[Profile Report for donor: España con ACNUR](../reports/iatiAnalysis-donor-espana-con-acnur.html)", 
"[Profile Report for donor: Republic of Korea](../reports/iatiAnalysis-donor-republic-of-korea.html)", 
"[Profile Report for donor: Italy (Government of)](../reports/iatiAnalysis-donor-italy-government-of.html)", 
"[Profile Report for donor: Japan for UNHCR](../reports/iatiAnalysis-donor-japan-for-unhcr.html)", 
"[Profile Report for donor: Ireland - Department of Foreign Affairs](../reports/iatiAnalysis-donor-ireland-department-of-foreign-affairs.html)"
)

# linkoperation <- generate_report(type = "operation")
# dput(linkoperation)
# linkoperation <- c()

##  Operations 

##`r paste0("- ", linkoperation, collapse = "\n")`
```
