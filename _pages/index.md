---
permalink: /index.html
title: 'FAIRDOM-SEEK'
layout: splash
classes:
    - wide

row1:
  - image_path: /assets/images/ISA-feature.png
    alt: "ISA"
    title: "Organise and store data"
    excerpt: "FAIRDOM-SEEK has adopted an ISATAB style structure for organising experiments and data."
    url: "/organise.html"    
  - image_path: /assets/images/Excel-feature.png
    alt: "Explore spreadsheets"
    title: "Explore spreadsheets"
    excerpt: "Excel spreadsheets and other documents can be explored without the need to download."
    url: "/explore.html"    
  - image_path: /assets/images/Model-simulation-feature.png
    alt: "Simulate SBML"
    title: "Simulate SBML models"
    excerpt: "Most models that conforms to the SBML, COPASI or Morpheus formats can be simulated within FAIRDOM-SEEK."
    url: "/simulate_sbml.html"
    
row2:
  - image_path: /assets/images/Who-feature.png
    alt: "Who is doing what"
    title: "Who is doing what, where?"
    excerpt: "We recognise that people, and their knowledge, are important."
    url: "/yellow_pages.html"    
  - image_path: /assets/images/Sharing-feature.png
    alt: "Sharing"
    title: "Flexible sharing controls"
    excerpt: "There is a lot of flexibility and control over who can see, download or edit your items."
    url: "/flexible_sharing.html"    
  - image_path: /assets/images/Rightfield-feature.png
    alt: "Rightfield"
    title: "Semantic templates"
    excerpt: "RightField enabled sheets allow rich semantic descriptions of data. Our Just Enough Results Model can be used with Rightfield."
    url: "/rightfield_templates.html"    
  
row3:
  - image_path: /assets/images/emt-management.png
    alt: "Extended Metadata Types management"
    title: "Extended Metadata"
    excerpt: "Define additional metadata attributes for a particular type, adhere to standards."
    url: "/extended_metadata.html"
  - image_path: /assets/images/DOI_logo.svg
    alt: "DOI logo"
    title: "Publishing and DOI"
    excerpt: "Set up a registration hub for your publications, manage DOIs."
    url: "/publishing_and_doi.html"
  - image_path: /assets/images/api-feature.png
    alt: "API feature"
    title: "API and programmatic access"
    excerpt: "The JSON API allows the searching, listing, reading, updating and creating. FAIRDOM-SEEK supports RDF export."
    url: "/api_and_programmatic_access.html"   
---



<div id='intro-text' markdown='1'>

![SEEK_logo](/assets/images/fairdom-seek-logo-alt.svg){: #front-screen-logo}


**FAIRDOM-SEEK** is an [open source](https://github.com/seek4science/seek) web-based cataloguing and commons platform, for sharing heterogeneous scientific research datasets, models or simulations, processes and research outcomes. 
It preserves associations between them, along with information about the people and organisations.


Underpinning FAIRDOM-SEEK is the [ISA infrastructure](http://isa-tools.org/), a standard framework for describing how individual experiments are aggregated into wider studies and investigations. 
Within FAIRDOM-SEEK, ISA has been extended and is configurable to allow the structure to be used outside of Biology.


Flexible and detailed sharing permissions are available to manage the catalogued items from early collaborations within projects, 
through to the publishing of final research results. At this point a DOI can be generated for individual items, or entire aggregates packaged as [Research Objects](http://www.researchobject.org/)


FAIRDOM-SEEK incorporates semantic technology, allowing sophisticated queries over the content. 
Metadata can be collected using standard Excel tools and processes, through the use of [RightField](http://rightfield.org.uk/).

A publicly available instance of a FAIRDOM-SEEK commons is available - as the [FAIRDOMHub](https://fairdomhub.org).

[![Fairdomhub](/assets/images/fairdomhub-logo.svg){: #fairdomhub-logo}](https://fairdomhub.org)

</div>

{% include feature_row id="row1" %}

{% include feature_row id="row2" %}

{% include feature_row id="row3" %}
