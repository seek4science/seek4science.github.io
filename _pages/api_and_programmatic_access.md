---
permalink: /api_and_programmatic_access.html
title: "API and Programmatic Access"
layout: single
---

FAIRDOM-SEEK includes a [JSON](https://www.json.org/) Application Programming Interface (API) that allows the searching, listing, reading, updating and creating of many items in your FAIRDOM-SEEK instance, along with their attributes.
The API supports Basic Authentication, OAuth and API Tokens, and can also be used without any authentication.

![Screenshot of the API in action](/assets/images/api-feature.png){: .screenshot}

FAIRDOM-SEEK supports RDF export (in Turtle format) and can be configured with a SPARQL endpoint. RDF generation will include [Extended Metadata](extended_metadata) when present for the attributes that include an identifier, and similarly some basic RDF is generated for Samples.
