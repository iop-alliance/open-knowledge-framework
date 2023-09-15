---
bibliography: /tmp/tmp-61rV0H284E961f.json
copyright:
  link: "https://creativecommons.org/licenses/by/4.0/"
  text: Creative Commons Attribution 4.0 International License
  type: CC-BY
csl: /app/dist/server/server/utils/citations/citeStyles/apa-6th-edition.csl
date:
  day: 26
  month: 01
  year: 2022
journal:
  publisher-name: Internet of Production Alliance
  title: Internet of Production Alliance
link-citations: true
title: Open Know-Where Specification
---

## 1. Introduction

This standard was initiated by the [Internet of Production
Alliance](https://internet-of-production.webflow.io/ "null") and
developed by an open-membership working group. It is designed to create
a consistent way of documenting and sharing information about
manufacturing capabilities to make it easier for people to identify
where hardware can be made locally or anywhere in the world.

This specification is designed to be adopted by anyone who collects or
shares data about manufacturing capabilities, including governments,
non-government organisations (NGOs), aid agencies, mapping communities,
makers and platforms. The standard defines data that meets the needs of
a broad range of use cases and purposes.

We call this "Open Know-Where".

Adopting the Open Know-Where standard will:

-   Improve the discovery of manufacturing facilities and equipment
    within the manufacturing industry and maker communities.

-   Enable someone who wants to access a manufacturing facility to
    discover who they should be contacting.

-   Improve relationships and collaboration between users and networks.

-   Make data about the location of manufacturing capabilities more
    easily discoverable and accessible when needed.

-   Enable better curation and management of data, so it can be
    collated, organised, queried and filtered.

-   Enable the curation of tools to extract the maximum value from the
    data.

Overall, the more universal the standard is, the more useful it will be.
The principle is that it is an open standard, whether or not the data it
is used to describe is released openly. 

The standard covers five concepts (classes) that mapping initatives
typically describe. For each concept, we have aimed to standardise the
properties to an appropriate level of granularity, which is helping
someone to find out where something can be made.

The five classes are:

-   Manufacturing Facility

-   Agent (Persons and Organisation)

-   Location

-   Equipment

-   Materials

Several aspects of the classes can be standardised through
classification and dictionaries. Using this approach means initiatives
and manufacturing facilities can more easily share, compare and
aggregate data. This is important, as currently there is no way to do
this without duplication of field names and data. The ability to easily
share data encourages the building of relationships and collaboration
between users and networks. This will lead to improved documentation,
networking, and discovery of mapping initiatives, manufacturing
facilities and equipment within the manufacturing sectors and maker
communities.

The intention is for data published under Open Know-Where, to be helpful
and informative, rather than authorative. We assume that any procurement
resulting from data published under this standard will still involve
direct or mediated interaction between the user/buyer and the facility.
Future versions of the specification will move towards more rigorous
approaches to defining information to enable distributed procurement
systems.

The project follows on from the success of the [Open
Know-How](https://openknowhow.org/ "null") documentation standard,
released in September 2019.

### 1.1. Scope

This specification defines a standard that provides a mechanism for the
discovery and exchange of the location of manufacturing capabilities and
where to get something made. This reflects the goal established by the
Internet of Production Alliance whose aim is to develop the enabling
technologies and infrastructures to support a global move to distributed
and local manufacturing.  

More information about the Internet of Production Alliance can be found
here: <https://global.us17.list-manage.com/subscribe?u=9ef0e368cc373faed18dbfc77&id=1e6d61b540>

The Open Know-Where specification defines a data model to:

-   Document the location of manufacturing capabilities globally.

-   Share information about manufacturing facilities and the
    manufacturing capabilities.

-   Improve networking within the manufacturing industry and maker
    communities.

The Open Know-Where specification provides the level of detail needed
for quick and simple documentation of manufacturing capbilites and
manufacuting facilities.

Although designed to be used by all, the intended audience is:

-   Mappers

-   Maker communities

-   Governments

-   Non-Government Organisations

-   Aid Agencies

-   Platforms listing local manufacturing capabilities 

The standard does not specify a data format or exchange protocols,
instead it aims to support the wide range of use cases from
spreadsheet-based datasets through to web-based platforms. 

### 1.2. Structure of this Document

This specification is divided into eight main sections:

1.  **Introduction** -- provides a broad overview of the background,
    scope and aim of this standard.

2.  **Data Model Diagram** -- provides an overall view of the Open
    Know-Where Data Model

3.  **Using the Data Model** -- provides guidance about how to use the
    data model, with answers to our most frequently asked questions.

4.  **Manufacturing Facility **-- defines properties relating to the
    manufacturing facility. Recommended classifications and formats are
    also provided for consistency.

5.  **Agent** -- defines properties relating to people and
    organisations. Recommended classifications and formats are also
    provided for consistency.

6.  **Location** -- defines properties relating to locations.
    Recommended classifications and formats are also provided for
    consistency.

7.  **Equipment** -- defines properties relating to equipment.
    Recommended classifications and formats are also provided for
    consistency.

8.  **Materials** -- defines properties relating to materials.
    Recommended classifications and formats are also provided for
    consistency.

9.  **Record Data **-- defines properties relating to record data.
    Recommended formats are also provided for consistency.

### 1.3. Technical Authoring

Technical authoring for version 1.0 has been undertaken by [Barbal
Limited](https://barbal.co/technical-and-professional-services/ "null").

The standard has been developed under the guidance of the Open
Know-Where working group following a series of qualitative interviews
with members of NGOs, aid agencies, mapping communities, makers and
platforms, and analysis into datasets shared by mapping initiatives and
organisations. From this initial research, a conceptual data model was
developed and circulated to stakeholders for comment. This document is
the formalisation of that data model and includes descriptions of each
aspect and guidance for how mapping initiatives can adopt the
standardised approach it prescribes.

### 1.4. Working Group Members

The following have contributed directly towards the development of this
specification.

  **Name**                   **Organisation**
  -------------------------- --------------------------------------------------------
  Andrés Barreiro            Wikifactory
  Charles Barrete            Field Ready
  Pierre-Alexis Ciavaldini   Makernet
  Liz Corbin                 Metabolic
  Guillaume Coulombe         Fab Labs Québec / Procédurable
  Marc-Olivier Duchame       Fab Labs Nation
  Andrew Lamb                Field Ready / Internet of Production Alliance
  Anna Sera Lowe             Manufacturing Change / Internet of Production Alliance
  Bryn John                  Field Ready
  Ben Oldfrey                UCL
  Nathan Parker              MakerNet.work
  James Ochuka               Juakali Smart
  Alessandra Schmidt         Make Works
  Hannah Stewart             RCA / Dark Matter Labs
  Aziz Wadi                  Field Ready
  Anna Waldman-Brown         MIT

More people than those listed here have been consulted, and we still
welcome any additional input from anyone who wants to get involved with
Open Know-Where.

## 2. Data Model Diagram

This diagram illustrates the classes, properties and relationships that
are introduced in the following main sections.

Whilst the model represents a relational schema between concepts, it is
not anticipated that all initiatives would use the whole model. The
schema is designed so that individual initiatives can focus only on
certain aspects and then data can be aggregated between data sets to
create richer, more powerful insight. 

For example an initiative to create an open database of equipment
capabilities by make and model could be combined with a mapping
initiative of maker spaces in a region which lists the make and model of
the equipment available to help someone work out where the specific
manufacturing processes they need can be accessed. 

![Open Know-Where data model diagram showing the relationships between
aspects of the standard\'s data
fields](https://assets.pubpub.org/556zgshv/71640173669266.png){#nql597kgrpu}

Open Know-Where data model

## 3. Using Open Know-Where

### 3.1. Can anyone use Open Know-Where?

Anyone can adopt the data model. It has been designed to be applied
across a variety of use cases, and provides a level of detail needed for
quick and simple mapping and recording of manufacturing capabilities and
manufacturing facilities. It can be used by formal and informal
organisations, and anyone who is mapping manufacturing capbabilities and
manufacturing facilities.

### 3.2. My resources are only available to members, will I have to give access for free?

No, this standard does not change your access models to your content.

### 3.3. Is this all about publishing data online?

Not necessarily. The primary purpose of Open Know-Where is to make it
easier to share information between mapping initiatives and other
entities who can make use of the data. We do not anticipate that many
data initiatives will choose to publish all the information openly
online and advise mapping initiatives to consider the privacy and
security of facilities, organisations and individuals and the
permissions (implied or explicit) they have for using the information
they have collected or recieved.  In some cases it will be prudent to
redact information to make is suitable for publishing online, e.g. state
the city and not a full address, or provide a login wall to access
contact information.

### 3.4. How is Classification Achieved?

[Naming
conventions](https://en.wikipedia.org/wiki/Naming_convention#:~:text=A%20naming%20convention%20is%20a,the%20names%20based%20on%20regularities. "null") allow
useful information to be deduced from regularity, will prevent confusion
among others who are collecting the same or similar data, and make it
easier for others to interpret your data.

By using a naming convention such as Wikipedia, the classification
simply provides a relevant Wikipedia URL and references the
corresponding Wikipedia article to the concept being described. For
example, through this way of classification, you can use the
corresponding Wikipedia article for a manufacturing process, to define
the process capability of a facility. The same can be applied for
equipment and materials. This manner of classification makes
manufacturing processes, equipment and materials easy to navigate and
provides consistency across the classification.

For example, for the metal-joining process of Brazing:

Wikipedia article: <https://en.wikipedia.org/wiki/Brazing>

### 3.5. How do I use the classification system?

To aid consistency, Open Know-Where recommends using an existing
classification system for Equipment, Manufacturing Processes and
Materials. This being Wikipedia.

**To classify equipment:**

To reference a facility has a piece of equipment, for example a
soldering iron, you would simply copy and paste the Wikipedia URL for a
soldering iron into the relevant field.

Wikipedia article: <https://en.wikipedia.org/wiki/Soldering_iron>

**To classify a manufacturing process:**

To classify a manufacturing process, for example soldering, you would
simply copy and paste the relevant Wikipedia URL for soldering into the
relevant field.

Wikipedia article: <https://en.wikipedia.org/wiki/Soldering>

**To classify a material:**

To reference a material, for example aluminium, you would simply copy
and paste the relevant Wikipedia URL for aluminium into the relevant
field.

Wikipedia article: <https://en.wikipedia.org/wiki/Aluminium> 

### 3.6. What data format is the data model designed to support?

The scheme is designed to support any structured data format. There is
no recommendation for how the data is stored or transferred.

### 3.7. Which standards does the specification use?

Rather than creating classifications for Equipment, Manufacturing
Processes and Materials we have used Wikipedia as reference.

The specification also references [ISO
8601](https://www.iso.org/iso-8601-date-and-time-format.html "null"),
the format YYYY-MM-DD for date, and [ISO
639-2](https://www.iso.org/iso-639-language-codes.html "null") or [ISO
639-3](https://iso639-3.sil.org/code_tables/639/data "null"), for
example "en-gb", to
record [Languages](https://standards.internetofproduction.org/pub/okw#languages "null").

### 3.8. Is Open Know-Where compatible with Open Know-How?

Open Know-Where is more detailed than Open Know-How version 1, which
only extends as far a signposting the documentation for making things.
We anticipate that later versions of Open Know-How will apply the same
approach as Open Know-Where for classifying equipment, materials and
processes so that the two standards will be fully interoperable.

### 3.9. What do the properties and sub-properties mean?

This section defines the layout used for defining properties. The list
of properties are laid out in sections four, five, six, seven and eight.
Each of these sections are navigated by the label assigned to each
individual field.

Sub-properties are used to group properties that relate to a specific
concept and that might be applicable in specific circumstance (e.g.
educational aspects of an innovation space).

For each property, the following specification is given where
applicable.

  **Label**        The human readable name assigned to the term.
  ---------------- ----------------------------------------------------------------------------------------------------
  **Fieldname**    The standardised computer readable fieldname. Typically this is the label expressed in camel case.
  **Definition**   A statement which represents the concept of the term.
  **Format**       The recommended practice for the field.
  **Note**         Additional points of note.
  **Example**      An illustration of how the term can be used.

### 3.10. Is the entire specification mandatory?

No aspect of the specification is mandatory. However the more
rigourously the specification is followed, the more useful the data will
be to others when shared.

The Open Know-Where working group intends to develop implementation
guides for specific use cases which may make certain aspects mandatory
in certain situations, e.g. Humanitarian applications may specify that
certain formats are used for fields or the Humanitarian Exchange
Language (HXL) is used for location.

### 3.11. Some of my data is sensitive and I don't want to share it. {#some-of-my-data-is-sensitive-and-i-dont-want-to-share-it}

That's fine. You should make a decision as to whether the information
you share will comprimise the trust, privacy or security of the
facilities or individuals the information relates to and apply a risk
based approach when deciding how you share data and who with.

### 3.12. Can I use Open Know-Where with spreadsheets?

Absolutely, the standard is designed to work with any structured data
format. The design is such that we expect that you will use separate
sheets within a workbook for each of the five classes and then use a
primary key or other spreadsheet functionality to link between them.

### 3.13. Which data serialisation format should I use?

Open Know-Where is compatible with any data serialisation format, for
example, XML, JSON, and YAML. It may be helpful to speak with who you
are exchanging data with to find out which format is most appropriate.

### 3.14. How does Open Know-Where deal with linked data across datasets?

We have not made any recommendation for how to link related data between
datasets, however each class has fields (or combination of fields) which
can be used as unique references. 

### 3.15. Will it be a lot of work to revise my existing datasets to be compatible with Open Know-Where?

Possibly. The data model doesn't require you to capture new data, as it
is not mandatory to use all the properties, but you may have to
restructure your data. The amount of work will be dependent on the size
of your datasets.

### 3.16. What if I want to capture information that isn't covered by Open Know-Where?

You are free to extend the fields you use in your own datasets, they
just might not be recognised by others. If you think your properties
would be a useful addition to the Open Know-Where specification itself
for others to use, contact the working group and recommend the
additions.  

## 4. Manufacturing Facility Properties

This class incorporates the important properties relating to
'Manufacturing Facility'. By facility we mean the workspace used for
manufacturing.

There are many different types of workspaces, ranging from industrial
facilities such as factories, to small scale production facilities such
as workshops, to makerspaces, even individual craftspeople working from
home. The aim of Open Know-Where is to incorporate and capture the
properties that are common to all of them, and also to define important
fields that are only applicable to certain types of manufacturing
facilities. For example, for innovation type spaces we have included
sub-properties such as Learning Resources, which is not relevant to all
manufacturing facilities but important to those within maker
communities.

Where properties are logically grouped, such as 'Human Capacity' and
'Innovation Space Properties', they are presented as collections of
sub-properties.

![Manufacturing facility data model diagram showing the relationship
between the standard\'s data fields related to manufacturing
facilities](https://assets.pubpub.org/c7wmzvbh/61640174340634.png){#ncg3eot8o7c}