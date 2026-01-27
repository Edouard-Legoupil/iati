# {iati} ![](reference/figures/hex-.png)

## Objective

A data package and analysis collection based on UNHCR contribution to
the [International Aid Transparency Initiative
(IATI)](https://reporting.unhcr.org/iati-international-aid-transparency-initiative)
that aims at:

- reshaping IATI extraction from a complex xml file structure to a more
  user-friendly tabular format with necessary look-up code tables
- offer easy to consume documentation on the data structure
- provide built-in ggplot2 visualization, aka a “**chart library**”
  around high level key questions on UNHCR programme. Those
  visualizations can be integrated in Operation Situation Analysis or
  Protection Monitoring Analysis.
- offer report templates with AI analsysis capabilities

## Rationale

While anyone can already ask a large language model to pull IATI date
and assemble an ad‑hoc analysis, that approach remains fundamentally
limited: every chat interaction produces a different framing, different
emphases, and different analytical pathways. By contrast, using AI to
generate narrative on top of a standardized set of charts and indicators
introduces a level of methodological consistency that simple chat-based
prompting cannot achieve. This framework ensures that every operation is
analyzed through the same **structured lens**, enabling comparability
across countries, time periods, and thematic areas. Instead of
reinventing the analysis each time, the AI is anchored in a stable
analytical model—reducing variance, improving coherence, and
guaranteeing that key questions are always addressed.

Just as importantly, this method produces narrative drafts that are
**“human‑in‑the‑loop ready”**: analysts can immediately focus on
refinement, nuance, and validation rather than on assembling first‑pass
descriptive text. The result is a workflow where AI accelerates the
routine narrative generation, while human experts retain control over
interpretation, context, and judgment.

## Install

    # install.packages("pak")
    pak::pkg_install("unhcr-americas/iati")

## Context

Extracting information from IATI can assist governments to plan and
manage their budgets; parliamentarians and citizens to better hold
governments accountable; community-based organisations to influence how
resources are used; and journalists, researchers and activists to
investigate the use and impact of the resources.

Information from Global Focus is translated into the IATI open data
standard and published using UNHCR’s IATI identifier: XM-DAC-41121. An
overview of the publication process is accessible through [IATI
Dashboard](http://dashboard.iatistandard.org/publisher/unhcr.md). Every
UNHCR operation world-wide is reported on for each year from 2016. This
includes financial information (budget, contributions, disbursements and
expenditure), office locations, and results at various levels of
activity. Activities for 2019 and onwards are be published as soon as
possible after they become available. This current package is updated a
much as possible….

### What is IATI?

Launched in Accra in 2008, the International Aid Transparency Initiative
([IATI](https://iatistandard.org/en/about/)) is a multi-stakeholder
initiative and international open data standard that aims to improve the
transparency and openness of both development and humanitarian
activities. In the 2016 Humanitarian grand Bargain, multiple
organisations also [committed
to](https://interagencystandingcommittee.org/greater-transparency)
“*Publish timely, transparent, harmonised and open high-quality data on
humanitarian funding within two years of the World Humanitarian Summit
in Istanbul” noting that parties “consider IATI to provide a basis for
the purpose of a common standard.*”

IATI provides a mechanism for the regular, automated publication of open
data on financial flows and also enables organizations to publish
information on their project or programming activities, including
information on monitoring, evaluation and results. Overall, 1000+
[humanitarian and development
organisations](https://www.iatiregistry.org/publisher/unhcr), including
government donors, multilateral and UN agencies and international and
local NGOs currently use the IATI Standard to publish information on who
funds them, where the money goes and the impact or outcome of their
activities. The use of IATI for Humanitarian actors is among the
commitment from the grand bargain as presented in the [dedicated
portal](https://www.humportal.org/about).

The International Aid Transparency Initiative (IATI) data to trace aid
flows from donor treasuries to their final end use. IATI is designed so
that people can trace development spending flows through the development
implementation chain, from one organization to other organizations,
right down to the final stage in the chain: spending on goods and
services. **Traceability** in IATI works by following the money as it
flows from organization to organization through the development
implementation chain. Provided that all organizations publish their
information, it is possible to assess how much of the total funding at
the beginning of the implementation chain is spent on goods and
services, and where the money is spent.

Data published to IATI is published in `activity` units, the core
building blocks of the data. **Activities** are usually projects, but
they can be any unit of development cooperation as defined by the
publisher, such as a program or a contract. Typically,an entire donor
country program is made up of a number of activities. Each activity is
given a unique identifier and contains details of all incoming and
outgoing transactions. Each transaction also has a unique identifier and
contains data covering,among other things,the date, the value, a
description, and details about the provider and receivers of the funds.
It is classified into one of three categories.

**Disbursement**: Outgoing funds placed at the disposal of a recipient
government or organization, or funds transferred between two separately
reported activities. Under IATI traceability standards the recipient of
a disbursement should also be required to report their activities to
IATI.

**Expenditure**: Outgoing funds spent directly on goods and services for
the activity. The recipients of expenditures fall outside of IATI
traceability standards and are considered to be the end of the
implementation chain. Therefore, an expenditure provided to a
non-country-based organization is considered to be funds \`not reaching
the country.

**Incoming fund**: Funds received for an activity, which can be from an
external or internal source.

**Organisations** can have different roles in IATI (each of them being
segregated into different “Organisation Types”): \* Reporting
Organisations, i.e. organisations voluntarily reporting about their aid
projects \* Implementations organisations, that actually implements the
activity.

The main concept are summarized in the table below from [IFRC IATI
Feasibility
Study](https://media.ifrc.org/ifrc/wp-content/uploads/sites/5/2018/03/IFRC-IATI-Feasibility-Study-Report-Final-2017-12-14.pdf) -
see also the
[Appendices](https://media.ifrc.org/ifrc/wp-content/uploads/sites/5/2018/03/IFRC-IATI-Feasibility-Study-Appendices-Final-2017-12-14.pdf)

![](reference/figures/iatifig3.png)

The diagram below provides also a summary of the main topics covered
through IATI:
![](https://raw.githubusercontent.com/unhcr-americas/iati/main/inst/iati.png)

### Key Visualisation on UNHCR Programme in the library (work-in-progress)

- What are the **most funded sectors** per country (Expenditure
  evolution per impact /outcome area)?  
- Who are the **main donors by country** in terms of number of projects
  and/or total budget?  
- Who are the **main implementing partners by country** in terms of
  number of projects and/or total budget?  
- What’s the breakdown of **Earmarking Type** (Un-earmarked, Tightly
  earmarked, etc.) from Donor Funds by Year?  
- What’s the level of **partnership between organisations** when
  implementing projects?  
- How much **expenditures compare to the initial budget** (weighted by
  \# PoCs / GPP in the country)?  
- How much **indicators** evolve over time against thresholds?

### Out of Scope: Humanitarian Funding at large

This package only includes UNHCR Data, as such the following questions
can not be adressed:

- What is the **share of funds received by different UN Agencies**
  (UNICEF, WFP, IOM, UNDP, UNOCHA)?
- How much donors **balance resources between different humanitarian
  crisis**?
- How much donors allocate budget between **humanitarian and development
  programmes** devoted to displacement crisis by key donors/region
- How much of donors funding goes to **migratory vs refugee issues**?
- What’s the **share of ODA** (Official Development Assistance) among
  the total flow of foreign aid per country?
- What’s the share of ODA going to **benefit of refugees**? (this can
  complement the measurement of [Global Refugee Compact Indicators
  related to ODA](https://www.unhcr.org/5cf907854.pdf#page=13))  
- What is the share of ODA allocated to **national actors**?  
- What’s the **share of Humanitarian assistance** within the total ODA?

## Contribute

The package includes different tables (`data`, `code` & `reference`)
together with a series of visualization functions, aka a “chart
library”“, (`show`) based on ggplot2

This package is built with the help of [fusen
package](https://thinkr-open.github.io/fusen/index.html) which allow to
easily maintain consistent documentation through a single notebook.

    fusen::inflate(flat_file = "dev/dev_unhcr_programme.Rmd", vignette_name = "UNHCR Programme")
