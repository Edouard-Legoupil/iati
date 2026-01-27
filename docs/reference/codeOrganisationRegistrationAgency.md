# codeOrganisationRegistrationAgency

The values from this codelist are used to identify the particular list
that an organisation identifier was drawn from. The codelist provides a
register of known identifier lists, including national company
registers, NGO directories and international and multilateral
organisation lists - along with guidance and online resources to help
locate the identifiers assigned to a specific organisation. As of 17
July 2017 this list is maintained by the org-id.guide project. Data
publishers can now search for and locate the relevant list for a
particular organisation identifier using the org-id.guide website.

The full register of identifier sources is also available to download in
XML, JSON and CSV formats.

IATI periodically replicates the codelist of identifier sources from
org-id.guide, to assist those accessing IATI documentation. However, it
is advised that the most up-to-date source is the org-id.guide project.

If org-id.guide does not contain an entry for the kind of organisation
you need to identify, you can make a request a new list is included in
the register following the guidance

## Usage

``` r
codeOrganisationRegistrationAgency
```

## Format

A data frame with 197 rows and 7 variables:

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

- `public-database`:

  logical public-database

## Source

<https://iatistandard.org/en/iati-standard/203/codelists/>

## Examples

``` r
{
knitr::kable(head(codeOrganisationRegistrationAgency, 10))
}
#> 
#> 
#> |code    |name                                      |description                                                                                                                                                                                                                                                                                                                        |category |url                                                                                  |status |public-database |
#> |:-------|:-----------------------------------------|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:--------|:------------------------------------------------------------------------------------|:------|:---------------|
#> |AE-ACCI |Ajman Chamber of Commerce and Industry    |There are 2 types of search available: Commercial search and Industrial search. You can also use an online enquiry form to find the required information. The contact details of Ajman Chamber and the heads of its sectors are also available.                                                                                    |AE       |https://www.ajmanchamber.ae/en/Pages/default.aspx                                    |active |FALSE           |
#> |AE-ADCD |Abu Dhabi Commercial Directory            |This register includes information on companies' Unified no., Membership no., name, address, phone number, email, activity etc.                                                                                                                                                                                                    |AE       |http://www.abudhabichamber.ae/English/E-Services/Pages/EServices-Page.aspx?sm=1&ty=s |active |FALSE           |
#> |AE-AFZ  |Ajman Free Zone Authority                 |The authority's website can be used to find its address, email and call center contacts. No clear search functionality directly on the website.                                                                                                                                                                                    |AE       |http://www.afz.gov.ae/                                                               |active |FALSE           |
#> |AE-DCCI |Dubai Chamber of Commerce and Industry    |This register includes information on companies name, address, phone number, website, activity and branches.                                                                                                                                                                                                                       |AE       |http://www.dcciinfo.com/                                                             |active |FALSE           |
#> |AE-DFSA |Dubai Financial Services Authority        |This register includes information on companies' name, DFSA reference number, address, phone number, legal status, services.                                                                                                                                                                                                       |AE       |https://www.dfsa.ae/Public-Register/Firm                                             |active |FALSE           |
#> |AE-DIFC |Dubai International Financial Centre      |This register includes information on companies' name, registration number, activity, phone number, address, etc.                                                                                                                                                                                                                  |AE       |https://www.difc.ae/public-register                                                  |active |FALSE           |
#> |AE-DMCC |Dubai Multi Commodities Centre            |Dubai Multi Commodities Centre is a Free Zone Authority established by the government of Dubai in 2002. The DMCC authority registers and licenses companies to operate in the DMCC Free Zone. N.B There is a 'Business Directory', however, this does not provide registration numbers[1] [1]: https://www.dmcc.ae/business-search |AE       |https://www.dmcc.ae/                                                                 |active |FALSE           |
#> |AE-FCCI |Fujairah Chamber of Commerce and Industry |There is no company information available directly from this registry, but Chamber of Commerce and Industry can be contacted via the form on the website, phone or email to request more information.                                                                                                                              |AE       |http://www.fujcci.ae/                                                                |active |FALSE           |
#> |AE-FFZ  |Fujairah Free Zone Company Listing        |There is no search available in this registry, but there is a list of companies with corresponding phone and fax numbers.                                                                                                                                                                                                          |AE       |http://www.fujairahfreetradezone.com/appdir/company-listing.php                      |active |FALSE           |
#> |AE-HFZA |Hamriyah Free Zone Authority              |A register that contains company names, addresses, phone numbers, emails, license numbers, activities, etc.                                                                                                                                                                                                                        |AE       |http://www.hfza.ae/en-us/directory.aspx                                              |active |FALSE           |
```
