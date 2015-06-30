Art Tracks is an initiative of the Carnegie Museum of Art that aims to turn provenance in to structured data by building a suite of open source software tools.  These tools transform traditional written provenenance records into searchable data, with an emphasis on existing data standards and a strong focus on building tools that are useful (and usable) across multiple institutions.
  
Once we have converted our provenance information into structured data, we can ask complex questions like “Which works in our collection were in the same city in the same year?” or “Which artworks in our collection were owned by an artist whose work is also in our collection?” By doing more with the data we already have, we can discover gaps in knowledge, shape collections policy, and better understand the ecosystem of the collection and the institution. 


----


## Overview of Phase One

Art Tracks: Phase One as a project is made up of several integrated tools and projects.  There are several core technologies involved:

#### Publications

The **CMOA Provenance Standard** is a strict superset of the AAM provenance standard, designed to resolve ambiguities and provide guidance and machine-readability.

**Museums & the Web Paper**, to be presented at Museums & the Web in April 2015.

#### Software Tools

The [**museum_provenance**](https://github.com/cmoa/museum_provenance) library is the core technology developed for this project.  It takes provenance records and converts them into structured, well-formatted data.

The [**Elysa**](https://github.com/cmoa/elysa) tool is a user interface designed for museum professionals.  It assists with verifying, cleaning, and modifying provenance records. 

The **`art_tracks`** library is an API layer developed in ruby that sits on top of the KE-Emu CMS at CMOA and converts into JSON and RDF, for use, parsing, and distribution.

The **Gallery Interactive** is a tool designed to take structured provenance data and present it to the public in interesting and visual ways.

A **search layer** has been created to allow for indexing and searching across the museum data.  This tool is built with [ElasticSearch](http://www.elasticsearch.org) and can be extended both for complete collection search, as well as provenance research.


---


*Initial funding for this project was provided in part by a generous grant by the [Institute of Museum and Library Services](http://www.imls.gov).*
{: .funding }