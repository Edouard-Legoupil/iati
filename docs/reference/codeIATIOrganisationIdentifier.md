# codeIATIOrganisationIdentifier

This is a list of organisation identifiers that is maintained by the
IATI Secretariat. The prefix for organisations on this list is XI-IATI
If a bona fide organisation is not registered with any recognised or
appropriate registration agency
(http://iatistandard.org/202/codelists/OrganisationRegistrationAgency/)
they should contact the IATI Technical Team who will exceptionally
allocate an organisation identifier using the XI-IATI prefix.

While some of these identifiers have been derived from DAC codes, this
‘meaning’ is not carried forward. i.e. IATI generated identifiers have
no intrinsic meaning. For general guidance about constructing
Organisation Identifiers, please see
http://iatistandard.org/organisation-identifiers/

## Usage

``` r
codeIATIOrganisationIdentifier
```

## Format

A data frame with 39 rows and 6 variables:

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
knitr::kable(head(codeIATIOrganisationIdentifier, 10))
}
#> 
#> 
#> |code           |name                                                                           |description                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |category |url                                                                               |status |
#> |:--------------|:------------------------------------------------------------------------------|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:--------|:---------------------------------------------------------------------------------|:------|
#> |XI-IATI-1001   |The Coca-Cola Export Corporation                                               |Subsidiary of The Coca-Cola Company responsible for marketing and export of soft drinks, bottled water, and other beverages and with links to the various charitable initiatives of The Coca-Cola Company, its subsidiaries and affiliates Coca-Cola charitable foundation. Based in Atlanta Georgia USA                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |NA       |http://www.coca-colacompany.com/                                                  |active |
#> |XI-IATI-1002   |United Mission to Nepal                                                        |The United Mission to Nepal (UMN) is a faith based INGO based in Kathmandu, and has worked in Nepal without interruption since 1954. UMN works through local partners in order to serve the people of Nepal, especially the poorest of those living in poverty, to pursue peace and justice for all and to address the root causes of their poverty. We do this by supporting communities in a transformation process focusing on health, education, sustainable livelihoods, peace-building and good governance.                                                                                                                                                                                                                                                                                                                                                          |NA       |http://www.umn.org.np/                                                            |active |
#> |XI-IATI-ACATBA |Association Centrafricaine de Traduction de la Bible et Alphabetisation        |ACATBA is a charity that exists to promote local language development, Bible translation, literacy and community development in the Central African Republic. They also provide training in basic business skills; this allows beneficiaries to begin income-generating activities and small businesses.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |NA       |http://www.wycliffe.net/organizations?entity=CXN&continent=AFR&country=CT         |active |
#> |XI-IATI-ADVZ   |Agência de Desenvolvimento do Vale do Zambeze                                  |Description: The Agência do Zambeze is a public-sector agency under the Ministry of Economics and Finance in Mozambique. The mission of the Agência do Zambeze is to promote the socio-economic and sustainable development of the Lower Zambezi River Basin.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |NA       |http://www.inm.gov.mz/?q=pt-pt/ag%C3%AAncia-de-desenvolvimento-do-vale-do-zambeze |active |
#> |XI-IATI-AGR    |AgResults                                                                      |AgResults is a $122 million collaborative initiative between the governments of Australia, Canada, the United Kingdom, the United States, and the Bill and Melinda Gates Foundation to incentivize the private sector to overcome market barriers and develop solutions to food security and agricultural challenges that disproportionately affect people living in poverty. The initiative designs and implements agriculture-focused prize competitions, also referred to as pay-for-results or pull mechanisms, which are innovative development finance programs that engage the private sector to work towards a defined goal to receive a monetary award.                                                                                                                                                                                                           |NA       |https://agresults.org/                                                            |active |
#> |XI-IATI-AIAS   |Administração de Infra-Estruturas de Águas e Saneamento                        |Description: AIAS manages the property of the secondary public systems for water supply and for the residual water drainage public systems in Mozambique promoting their autonomous efficient and financially feasible operational management through assignment to private operators or other third party entities.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |NA       |http://www.aias.gov.mz/                                                           |active |
#> |XI-IATI-AJS    |Associations des Juristes Sénégalaises (AJS)                                   |The Association des Juristes Sénégalaises (AJS) is an association of women lawyers who promote and contribute to the protection of the rights of individuals, particularly women and children.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |NA       |http://www.femmesjuristes.org                                                     |active |
#> |XI-IATI-ATTIC  |Association of Technicians in Information Technology and Communication (ATTIC) |ATTIC, a non-political non-profit association in Republic of Chad, aims to help develop and integrate the promotion of information and communication technologies in the development policy of the formal and non-formal sectors, to fight against food insecurity and poverty, by strengthening the means of vulnerable households, refugees, returnees and internally displaced persons, and by providing socio-professional training and integration for vulnerable groups.                                                                                                                                                                                                                                                                                                                                                                                             |NA       |Website is still in progress                                                      |active |
#> |XI-IATI-BBDN   |Bangladesh Business & Disability Network                                       |The Bangladesh Business and Disability Network (BBDN) is a voluntary group of representatives from business, industry, employers’ organizations and selected non-governmental and disabled peoples’ organizations. BBDN has a primary purpose of facilitating disability and work place diversity in Bangladesh from the perspective of the business and human rights cases.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |NA       |https://www.bbdn.com.bd/                                                          |active |
#> |XI-IATI-EBRD   |European Bank for Reconstruction and Development                               |Description: Who we are - The EBRD is investing in changing peoples' lives and environments from central Europe to Central Asia, the Western Balkans and the southern and eastern Mediterranean region. With an emphasis on working with the private sector, we invest in projects, engage in policy dialogue and provide technical advice that fosters innovation and builds sustainable and open-market economies. What we do - The EBRD provides direct financing for well structured, financially robust projects of all sizes (including many small businesses), both directly and through financial intermediaries such as local banks and investment funds. The Bank works mainly with private sector clients, but also finances municipal entities and publicly owned companies. Our principal financing instruments are loans, equity investments and guarantees. |NA       |http://www.ebrd.com/home                                                          |active |
```
