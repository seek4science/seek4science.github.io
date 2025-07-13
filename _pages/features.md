---
permalink: /features.html
title: 'Features'
layout: 'single'
redirect_from: '/about.html'
---


## Key features

**Data Catalogue** – The data catalogue in FAIRDOM-SEEK includes raw [Datasets](https://fairdomhub.org/data_files), [Documents](https://fairdomhub.org/documents), [Standard Operating Procedures(SOPs)](https://fairdomhub.org/sops), [Models](https://fairdomhub.org/models), [Publications](https://fairdomhub.org/publications) and [Presentations](https://fairdomhub.org/presentations). All data are grouped by projects, and associated with the researchers who produced them. Documents can be put into [collections](https://fairdomhub.org/collections). 

In order to encourage [sharing of data](flexible_sharing.html) we allow researchers flexibility in the formats they upload and share their data in. This means data formats in the FAIRDOM-SEEK catalogue can vary. We do offer a set of “best practice” guidelines for researchers who want to make their data available and usable to the widest possible audience.
The sharing policy and permissions for assets can be changed in batch.

Most common formats allow viewing within the browser, without a download, with additional enhanced features for spreadsheets and SBML models. The contents of [Excel spreadsheets can be explored](explore.html) in the browser.
Multiple data files can be registered at once by uploading a zip file. 
All data and information added to FAIRDOM-SEEK is searchable using key-words. 

**Versioning** – All data is stored using versioning, selectable privacy, and static URLs. Versioning and privacy settings ensure that you can share your most recent data, with who you choose. Static URLs ensure that you can be credited directly for all shared work.
Individual versions can have their visibility controlled, allowing past versions to be completely hidden if desired.

**Model simulation and annotation** – if models follow the [SBML standard](http://sbml.org/), they can be [simulated from within FAIRDOM-SEEK](simulate_sbml.html) with [JWS Online](http://jjj.mib.ac.uk/).
[COPASI](http://copasi.org/) models can be interpreted and manipulated directly from the browser. 
[Morpheus](https://morpheus.gitlab.io/) models can be simulated directly from the browser.

**Access Control** – Data will go through a research lifecycle between collection and publication. In a competitive academic environment it is important that the data can be shared with collaborators, and then the wider community at appropriate points within the life-cycle. FAIRDOM-SEEK allows users to keep their uploaded data entirely private, to share between individuals, then across entire projects, until eventually making it public upon publication.
A gatekeeper role can be assigned to manage sharing of a project's assets.

**People index** – FAIRDOM-SEEK contains an [index of people](yellow_pages.html) where users can browse, or keyword-search, profiles of the projects, groups and people that contribute to the data on the site. People can describe their areas of expertise, which allows other users to quickly identify the right people to approach regarding specialist enquiries and collaboration proposals.
Extra identifying information, such ORCID and affiliation, can be added for each creator, even if they are not registered in FAIRDOM-SEEK.

**Samples** – FAIRDOM-SEEK has a flexible samples framework that allows users to generate templates for sample metadata. Samples can be data, or laboratory samples. The framework integrates with Rightfield sheets, so that semantically-enhanced title sheets can be included with the data. The default Rightfield sheet uses the JERM and allows automatic generation and linking of the data files to an assay.
Sample attributes can be limited to controlled vocabularies backed by an ontology.

**Extended Metadata** – FAIRDOM-SEEK allows items to be customized with [additional typed metadata](extended_metadata.html), similar to samples, and was used to support [MIAPPE](https://www.miappe.org/).
Extended Metadata can be nested, i.e one Extended Metadata type definition can include a reference to another, and these will be nested together in a single form.

**ISA and Interlinking** – Data in FAIRDOM-SEEK gain increased value and usability when they are described within the context of an experimental process. 
Multiple experiments will be carried out as part of a single Study, and that study may be part of a wider overall funded Investigation. 
In FAIRDOM-SEEK we adopt the [ISATAB structure (Investigation, Studies, Assays)](organise.html) which is a community standard for describing links between Omics experiments. 
We believe that many aspects of the ISA framework are equally appropriate for describing experiments beyond Omics and Biology, so allow this framework to be applied to all data.

Beyond the ISA framework, FAIRDOM-SEEK allows data to be interlinked within the site itself in order to describe their relationship.

**Publishing and licensing** – If research resulted in a [publication](publishing_and_doi.html), this can also be registered with FAIRDOM-SEEK (including accreditation to relevant people) using a [PUBMED](http://www.ncbi.nlm.nih.gov/pubmed) identifier or [DOI](http://www.doi.org/), 
and linked to the assets involved in that research – allowing other researchers access to use, examine, or validate the data that would otherwise be unavailable through the publication alone.
FAIRDOM-SEEK can be set up as [registration hub](publishing_and_doi.html) for your publications and issue DOIs.

We recommended giving a license to public resources in FAIRDOM-SEEK to clarify under what terms they may be used. A Project administrator may specify the default license for their project which is automatically selected when creating a new item, but can be changed by the user if necessary.

**API and programmatic access** – The [JSON API](api_and_programmatic_access.html) allows the searching, listing, reading, updating and creating of many items in your FAIRDOM-SEEK instance, along with their attributes. FAIRDOM-SEEK supports RDF export (in Turtle format) and can be configured with a SPARQL endpoint.

**Bioschemas support** – A **sitemap.xml** is generated for all public content, improving indexing by the main search engines, and supports [Bioschemas](https://bioschemas.org/) scraping. Bioschemas (and therefore [schema.org](https://schema.org/)) metadata is generated for each asset type in FAIRDOM-SEEK, using the common Bioschemas profiles such as Project, Sample and DataSet.

## Bespoke Development

If you are interesting in having features added, or in having FAIRDOM-SEEK link to specific resources (e.g. an institute or national repository), 
or other bespoke development, then contact us for a consultation [support@fair-dom.org](mailto:support@fair-dom.org)