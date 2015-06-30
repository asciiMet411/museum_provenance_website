## Overview of Phase One

Art Tracks is an initiative of the [Carnegie Museum of Art (CMOA)](http://www.cmoa.org) that aims to turn provenance in to structured data by building a suite of open source software tools.  These tools transform traditional written provenenance records into searchable data, with an emphasis on existing data standards and a strong focus on building tools that are useful (and usable) across multiple institutions.
  
Once we have converted our provenance information into structured data, we can ask complex questions like “Which works in our collection were in the same city in the same year?” or “Which artworks in our collection were owned by an artist whose work is also in our collection?” By doing more with the data we already have, we can discover gaps in knowledge, shape collections policy, and better understand the ecosystem of the collection and the institution. 


----

## Publications

The [**CMOA Provenance Standard**](standard.md) is a strict superset of the AAM provenance standard, designed to resolve ambiguities and provide guidance and machine-readability. A draft version has been published.  Examples of [records written using this style](example-records.md) are available.

[**Art Tracks: Visualizing the stories and lifespan of an artwork
**](http://mw2015.museumsandtheweb.com/paper/art-tracks-visualizing-the-stories-and-lifespan-of-an-artwork/), was a paper on our work to-date on Art Tracks, presented at Museums & the Web in April 2015.

> **Abstract**

> The Carnegie Museum of Art is attempting to structure provenance data so curators, scholars, and software developers can create visualizations that answer questions that would be difficult or impossible to answer without computer assistance. Provenance, the written description of the history of ownership and custody of art, is typically written as a list of the periods, places, and owners of an artwork. It captures the current best understanding of this history in a succinct and precise manner, and illustrates the gaps and uncertainties that still remain. Provenance is typically written as semi-structured text, following an institution-defined format. It would be useful to have a structured, computer-readable format for this data, allowing for search, visualization, and aggregated research. The American Alliance of Museums suggested standard, widely used across museums, is not defined with enough specificity to allow automated extraction of the structured data contained within provenance texts. Also, the provenance record model in collection management systems (CMS) is often not designed for structured data or does not provide a way to verify that the provenance text matches the structured data. A comprehensive text-based provenance standard, paired with a software library that can parse records written using this standard and convert them into structured data, would allow existing workflows to remain in place while allowing structured data to be automatically extracted from provenance records. The records could continue to be stored within existing CMS databases but contain machine-readable data for use in research and visualization. Outside of data itself, the stories these objects hold are often moving and sometimes astonishing. This ability to ask impossible questions and receive answers previously inaccessible across a museum’s collection and (eventually) across many museums’ collections is a resource art historians and scholars will find extremely valuable.
{: .abstract}

---

## Software Tools

The [**museum_provenance**](https://github.com/cmoa/museum_provenance) library is the core technology developed for this project.  It takes provenance records and converts them into structured, well-formatted data.

The [**Elysa**](https://github.com/cmoa/elysa) tool is a user interface designed for museum professionals.  It assists with verifying, cleaning, and modifying provenance records. 

---


*Initial funding for this project was provided in part by a generous grant by the [Institute of Museum and Library Services](http://www.imls.gov).*
{: .funding }