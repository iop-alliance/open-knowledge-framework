Manufacturing Facility data model

### 4.1. Name

**Definition: **Name of the facility.

**Format: **Provide the name of the facility.

### 4.2. Location

**Definition: **Location of the facility.

**Format: **Uses
the [Location](https://standards.internetofproduction.org/pub/okw#location-properties "null") class.

### 4.3. Owner

**Definition: **An [Agent](https://standards.internetofproduction.org/pub/okw#agent-properties "null") who
owns or manages the facility.

**Format: **Uses
the [Agent](https://standards.internetofproduction.org/pub/okw#agent-properties "null") class.

### 4.4. Contact

**Definition: **An [Agent](https://standards.internetofproduction.org/pub/okw#agent-properties "null") who
is the contact for enquiries about making.

**Format: **Uses
the [Agent](https://standards.internetofproduction.org/pub/okw#agent-properties "null") class.

### 4.5. Affiliation

**Definition: **The [Agent](https://standards.internetofproduction.org/pub/okw#agent-properties "null")(s)
who the manufacturing facility is affiliated with.

**Format: **Uses
the [Agent](https://standards.internetofproduction.org/pub/okw#agent-properties "null") class.

**Note: **An affiliation can be used to define the facility type, for
example an affiliation with FabLabs.org implies that the facility is a
FabLab.

### 4.6. Facility Status

**Definition: **Status of the facility.

**Format: **Use of one the following:

-   Active

-   Planned

-   Temporary Closure

-   Closed

### 4.7. Opening Hours

**Definition: **Hours in which the facility operates.

**Format: **Free text.

### 4.8. Description

**Definition:** Description of the facility.

**Format: **Free text.

### 4.9. Date Founded

**Definition: **Date the facility was founded.

**Format: **Recommended practice is to use [ISO
8601](https://www.iso.org/iso-8601-date-and-time-format.html "null"),
i.e. the format YYYY-MM-DD.

**Note: **It is acceptable to include only the Year (YYYY) or year and
month (YYYY-MM).

### 4.10. Access Type

**Definition: **How the manufacturing equipment is accessed.

**Format: **Use one of the following:

-   Restricted (only certain people (e.g. staff members) can use the
    equipment)

-   Restricted with public hours (the equipment can be used by the
    public during limited hours)

-   Shared space (the facility is a shared workspace where access is by
    qualifying criteria (e.g. rental of a desk or workspace))

-   Public (anyone may use the equipment (e.g. training may be required
    and other restrictions may apply))

-   Membership (access requires membership, which is available to the
    public or a certain demographic)

**Note:** For facilities, use this field on a general-terms basis (i.e.
if most equipment is available to members, but certain equipment
requires staff to operate use Membership). This field can also be used
as a property of individual equipment where a facility has different
aspect types for different equipment.

### 4.11. Wheelchair Accessibility

**Definition: **Whether the manufacturing facility is wheelchair
accessible.

**Format: **Free text.

### 4.12. Equipment

**Definition: **The equipment available for use at the manufacturing
facility.

**Format: List the equipment available using
the **[Equipment](https://barbal.co/the-open-know-where-specification/#4ff07f8c-32cd-415c-bceb-1704defc1c26 "null") class.

### 4.13. Manufacturing Processes

**Definition: **Typical manufacturing processes undertaken at the
facility.

**Format: Reference the relevant Wikipedia article.**

**Note: **For instructions how to do this, please see [section
3.5](https://barbal.co/the-open-know-where-specification/#a415a370-91a1-4ec2-a9fb-a0fc05a9be1e "null").

### 4.14. Typical Batch Size

**Definition: **Typical batch size output.

**Format: ** Use one of the following:

-   0 -- 50 units

-   50 -- 500 units

-   500 -- 5000 units

-   5000 + units

### 4.15. Size / Floor Size

**Definition: **The size or floor size of a manufacturing facility.

**Format: **Integer. Unit: square metres (sqm).

**Note: **This helps a prospective user gauge the scale of a
manufacturing facility.

### 4.16. Storage Capacity

**Definition: **Storage Capacity of the manufacturing facility.

**Format:** Free text.

**Note: This helps a prospective user gauge how much storage capacity a
manufacturing facility has for producing and storing stock.**

### 4.17. Typical Materials

**Definition: **Typical materials used by the facility.

**Format: Uses
the **[Materials](https://standards.internetofproduction.org/pub/okw#materials-properties "null")** class.**

### 4.18. Certifications

**Definition: **Certifications obtained by the facility.

**Format: **List the certifications.

**Note: **Knowledge of these is imperative informal manufacturing and
procurement. For example, aid agencies would be able to see which
manufacturing facilities have particular manufacturing licenses, such as
medical manufacturing.

### 4.19. Backup Generator

**Definition:** Whether a manufacturing facility has a backup generator.

**Format: **TRUE / FALSE

**Note: Knowledge of this is particiularly useful in places where there
are frequent power outages.**

### 4.20. Uninterrupted Power Supply

**Definition: **Whether a manufacturing facility has an uninterrupted
power supply.

**Format: **TRUE / FALSE

### 4.21. Road Access

**Definition: **Whether a manufacturing facility has road access.

**Format: **TRUE / FALSE

### 4.22. Loading Dock

**Definition: **Whether a manufacturing facility has a loading dock.

**Format: TRUE / FALSE**

### 4.23. Maintenance Schedule

**Definition: **The maintenance schedule of a manufacturing facility.

**Format: **Free text.

### 4.24. Typical Products

**Definition:** Typical products produced by the facility.

**Format: **List the typical products produced.

### 4.25. Partner / Funder

**Definition: **The [Agent](https://standards.internetofproduction.org/pub/okw#agent-properties "null") which
partners or funds the facility.

**Format: Uses
the **[Agent](https://standards.internetofproduction.org/pub/okw#agent-properties "null") class.

### 4.26. Customer Reviews

**Definition: **Customer reviews of the facility.

**Format: **Free text.

### 4.27. Circular Economy sub-properties

This section relates to Circular Economy. The definition of Circular
Economy used can be
found [here](https://en.wikipedia.org/wiki/Circular_economy "null").

#### 4.27.1. Circular Economy

**Definition: **Whether a manufacturing facility applies Circular
Economy principles.

**Format: **TRUE / FALSE

#### 4.27.2. Description {#description}

**Definition: **Definition of how Circular Economy principles are
applied.

**Format:** Free text.

#### 4.27.3. By-products

**Definition: **List of the by-products produced.

**Format: **Uses
the [Materials](https://standards.internetofproduction.org/pub/okw#materials-properties "null") class.

### 4.28. Human Capacity sub-properties

**Definition: **The human capacity of the facility sub-properties.

#### 4.28.1. Headcount

**Definition: **The headcount of the facility in FTE, using definition
provided [here](https://en.wikipedia.org/wiki/Full-time_equivalent "null").

**Format: **Integer.

**Note: **It is useful for a user / NGO / aid agency to determine the
scale of the facility.

#### 4.28.2. Maker

**Note:** Identified as future work.

### 4.29. Innovation Space sub-properties

**Definition: **The innovation space sub-properties.

#### 4.29.1. Staff

**Definition:** Number of staff supporting the innovation and
educational aspects of the facility.

**Format: **Integer.

**Note: **It is useful to help determine the scale of the facility.

#### 4.29.2. Learning Resources

**Definition: **The learning resources available at the facility.

**Format: **List the learning resources.

**Note: **It is useful for a user to be aware of any learning resources
-- courses, educational classes etc., a manufacturing facility may have
/ run.

#### 4.29.3. Services

**Definition: **The services provided by a manufacturing facility.

**Format: **List the services provided.

#### 4.29.4. Footfall

**Definition: **The footfall at a manufacturing facility.

**Format: **Integer.

**Note: **It is useful to help determine the scale of the manufacturing
facility.

#### 4.29.5. Residencies

**Definition: **Where residencies are available at a manufacturing
facility.

**Format:** TRUE / FALSE

## 5. Agent Properties

This class incorporates properties relating to 'Agent'. Mapping
initiatives capture different relationships, ranging from owners,
managers, funders, contact, people, members, and so on. In order to
categorise this, we have standardised the properties of people and
organisations, or 'agent' as an umbrella term. We have decided to keep
people and organisations combined in a single class because they are
often interchangeable. For example, an owner could be a person or an
organisation.

Some properties such as 'Contact' and 'Social Media', have been
developed further to include important sub-properties. For example, the
inclusion of 'Social Media' sub-properties was incorporated as many
mapped Fab Labs did not have their own URL website, but used Facebook to
promote their facility, projects and capabilities.

Where properties are logically grouped, they are presented as
collections of sub-properties.

![](https://assets.pubpub.org/6hvlk6nd/21640175866625.png){#n1a61sxlriw}

Agent data model

### 5.1. Name {#name}

**Definition: **The name of
the [Agent](https://standards.internetofproduction.org/pub/okw#agent-properties "null").

**Note: **This could be a name of a person or an organisation.

### 5.2. Location {#location}

**Definition: **A [Location](https://standards.internetofproduction.org/pub/okw#location-properties "null").

**Format: **Uses
the [Location](https://standards.internetofproduction.org/pub/okw#location-properties "null") class.

### 5.3. Contact Person

**Definition: **An [Agent](https://standards.internetofproduction.org/pub/okw#agent-properties "null") who
is the key point of contact for a manufacturing facility or
organisation.

**Format:** Provide the name of
the [Agent](https://standards.internetofproduction.org/pub/okw#agent-properties "null").

### 5.4. Bio

**Description: **A description of a person or an organisation.

**Format: **Free text.

### 5.5. Website

**Definition: **Website address.

**Format: **Provide the relevant URL.

### 5.6. Languages

**Definition: **Languages used by a person or an organisation.

**Format: **[ISO
639-2](https://www.iso.org/iso-639-language-codes.html "null") or [ISO
639-3](https://iso639-3.sil.org/code_tables/639/data "null"), for
example "en-gb".

**Note: **Often manufacturing facilities may be able to provide services
dealing in more than one language.

### 5.7. Mailing List

**Definition: **Mailing list for an organisation.

### 5.8. Images / Media

**Definition: **Images / Media of a person, an organisation, or relating
to the manufacturing facility.

### 5.9. Contact sub-properties

**Description: **Defined contact information.

#### 5.9.1. Landline

**Definition: **A landline telephone number to contact the facility,
person or organisation.

**Format: **Provide the telephone number.

#### 5.9.2. Mobile

**Definition: A mobile telephone number to contact the facility, person
or organisation.**

**Format: **Provide the telephone number.

#### 5.9.3. Fax

**Definition: A fax number to contact the facility, person or
organisation.**

**Format: **Provide the fax number.

#### 5.9.4. Email

**Definition: **An email address to contact the facility, person or
organisation.

**Format: **Provide the email address.

#### 5.9.5. WhatsApp

**Definition: **A WhatsApp number to contact the facility, person or
organisation.

**Format: **Provide the telephone number.

**Note: **In some instances, users contact the manufacturers through
WhatsApp.

### 5.10. Social Media sub-properties

**Description: **Defined social media information.

#### 5.10.1. Facebook

**Definition: **Facebook page URL.

**Format: **Provide the relevant URL.

**Note: **Facebook is an important platform for contacting Fablabs /
other manufacturing facilities. For example, in the Philippines, a
Facebook group has been created for all Fablabs to interact through.

#### 5.10.2. Twitter

**Definition: **Twitter page URL.

**Format: **Provide the relevant URL.

**Note: Manufacturing facilities often promote themselves, their
activities and projects on Twitter.**

#### 5.10.3 Instagram

**Definition: **Instagram page handle.

**Format:** Provide the relevant Instagram handle.

**Note: Manufacturing facilities often promote themselves, their
activities and projects on Instagram.**

#### 5.10.4 Other URLs

**Definition: **Other URLs.

**Format: **Provide the relevant URLs.

**Note: Other examples of social media associated with a manufacturing
facility, organisation or person, unclassified by this standard, but can
also be included. For
example, **[**fablabs.io**](https://fablabs.io/labs "null")** or **[**hackerspaces.org**](https://hackerspaces.org/ "null")**.**

## 6. Location Properties

This class incorporates the important properties relating to 'Location'.

A simple standardised way of capturing geographical information is
imperative -- to be able to use a 'Manufacturing facility' or
'Equipment', a user needs to know its location. The properties below
describe the core characteristics which are needed for data collection.

Recording a geographical location differs globally. In the developed
world, an 'Address' such as a street address, is the norm for recording
places of interest. Whereas, in some countries, a description of the
location -- i.e. 'near the school, on this corner', is an adequate
description of location. When recording data, the latter qualitative
data is subjective, and difficult to quantify. As such, an addressing
system which is not a street address is incredibly useful. Consequently,
the application of '[GPS
coordinates](https://standards.internetofproduction.org/pub/okw#gps-coordinates "null")'
and '[What 3
Words](https://standards.internetofproduction.org/pub/okw#what-3-words-sub-properties "null")'
have been integrated into the Open Know-Where data model. Both 'GPS
coordinates' and 'What 3 Words' are already in use by many NGOs and Aid
Agencies when recording the 'Location' of manufacturing facilities
and/or 'Equipment'.

For compatibility with the [Humanitarian Exchange
Language](https://hxlstandard.org/standard/1-1final/ "null"), use
the [HXL hashtag
chooser](https://hxlstandard.github.io/hxl-hashtag-chooser/ "null").

Where properties are logically grouped, they are presented as
collections of sub-properties.

![](https://assets.pubpub.org/6oo7rpuq/21640188254529.png){#nriusmhjam5}

Location properties data model

### 6.1. Address

**Definition: **Address relating to a manufacturing facility, person or
organisation.

**Format: **Use the defined Address sub-properties:

-   Number

-   Street

-   District

-   City

-   Region

-   Country

-   Postcode

**Note: **Address has been standardised to include these fields for ease
of use, discoverability and merging data sets.

For compatibility with the [Humanitarian Exchange
Language](https://hxlstandard.org/standard/1-1final/ "null"), use
the [HXL hashtag
chooser](https://hxlstandard.github.io/hxl-hashtag-chooser/ "null").

### 6.3. GPS Coordinates

**Definition: **The relevant GPS coordinates.

**Format: **Provide the relevant GPS coordinates, using [Decimal
Degrees](https://en.wikipedia.org/wiki/Decimal_degrees#:~:text=Decimal%20degrees%20(DD)%20express%20latitude,as%20OpenStreetMap%2C%20and%20GPS%20devices. "null").

**Note: ** GPS coordinates are a common standardised way of detailing a
location, used by many aid agencies and mapping initiatives.

### 6.4. Directions

**Definition: **Directions to manufacturing facility, person or
organisation.

**Format: **Free text.

**Note: **This qualitative data field may be helpful for a difficult to
find location, or in an area where the standard address format is
irrelevant.

### 6.5. What 3 Words sub-properties

**Definition: **The What 3 words address for the location.

#### 6.4.1. What 3 Words

**Definition: **What 3 Words phrase for location.

**Format: **State the What 3 Words phrase.

**Note:** Often informal settlements, or developing countries do not
have street addresses, and communicating GPS coordinates can be tricky
and error-prone. What 3 Words is an alternative geospatial address
system.

Every location has been a 3m x 3m grid square with a 3 word address.
Meaning you can collect, validate and provide any location within a 3m x
3m radius with just 3 words. For example: Barbal's office in Bristol is
recorded as '///shares.parks.alone'.

#### 6.4.2. Language

**Definition: **Language What 3 Words has been recorded in.

**Format: **[ISO
639-2](https://www.iso.org/iso-639-language-codes.html "null") or [ISO
639-3](https://iso639-3.sil.org/code_tables/639/data "null"), for
example "en-gb".

**Note: **What 3 Words is available in 43 different languages and the
words for an address are not direct translations of each other.

## 7. Equipment Properties

This class incorporates the properties relating to Equipment. It
provides a simple standardised way of capturing the manufacturing
capabilities of equipment.

A key aspect which arose, is the scope, and specifically -- what are we
trying to capture? For example, only machines and digital equipment? Or
can we capture hand tools, IT equipment, software, and so on?

Knowing that a CNC router may be important may be useful in decision
making for deciding where to get something made, but generic hand tools
may not, but that does not preclude them from being included when
documenting. This resulted in needing a simple classification system
which would standardise a wide variety of Equipment.

The potential list of properties for Equipment is boundless but, Open
Know-Where aims to standardise as many as possible. We expect this list
to grow with time with different recommended properties for different
classes of equipment/tools.

Where properties are logically grouped, they are presented as
collections of sub-properties. 

![](https://assets.pubpub.org/0u0vpclg/71640188545208.png){#npvtnepjs4z}

### 7.1. Equipment Type

**Definition: **Classification of Equipment.

**Format: **Provide the Wikipedia URL for the relevant Equipment Type.

**Note: **For instructions how to do this, please see [section
3.5](https://standards.internetofproduction.org/pub/okw#how-do-i-use-the-classification-system "null").

### 7.2. Manufacturing Process

**Definition: **Manufacturing process the Equipment is capable of.

**Format: **Provide the Wikipedia URL for the relevant manufacturing
process.

**Note: **For instructions how to do this, please see [section
3.5](https://standards.internetofproduction.org/pub/okw#how-do-i-use-the-classification-system "null").

### 7.3. Make

**Definition: **Make of the piece of equipment.

**Format: **Provide the make of the model.

**Note:** Provides detailed information about a piece of equipment/tool.
For example, you can design generically for a 3D printer, or you can
design for a specific make or model of 3D printer.

### 7.4. Model

**Definition: **Model of the piece of Equipment.

**Format: **Provide the name of the model.

**Note: **Provides detailed information about a piece of equipment. For
example, you can design generically for a 3D printer, or you can design
for a specific make or model of 3D printer.

### 7.5. Serial Number

**Definition: **Serial number of the piece of Equipment.

**Format: **Provide the serial number of the Equipment.

### 7.6. Location {#location}

**Definition: **Location of the equipment.

**Format: **Uses [Location](https://barbal.co/the-open-know-where-specification/#e234eb65-ff36-4343-8c4a-cb9d7c02342f "null") class.

### 7.7. (Skills Required)

***Identified as future work.***

### 7.8. Condition

**Definition: **The condition of the piece of equipment.

**Format: **State the condition of the piece of equipment.

**Note:** This provides a user with information surrounding the quality
of a piece of equipment/tool, and whether it can complete the task they
need it for.

### 7.9. Notes

**Definition: **Additional information about the piece of equipment.

**Format: **Free text.

### 7.10. Owner {#owner}

**Definition:** The owner of a piece of equipment.

**Format: **Uses
the [Agent](https://standards.internetofproduction.org/pub/okw#agent-properties "null") class.

**Note:** To be used when the owner is not the manufacturing facility.

### 7.11. Quantity

**Definition: **Quantity of specific piece of equipment.

**Format:** Integer.

**Note:** This provides information surrounding the size and scale of a
manufacturing facility and implicates batch size.

### 7.12. Throughput

**Definition: **The throughput of the piece of equipment.

**Format: **Free text.

### 7.13. Power Rating

**Definition: **The power rating of the piece of equipment.

**Format: **Integer. Unit: W.

### 7.14. Materials Worked

**Definition: **The materials that can be used with the piece of
equipment.

**Format: **Uses
the [Materials](https://standards.internetofproduction.org/pub/okw#materials-properties "null") Classification. 

### 7.15. Maintenance Schedule {#maintenance-schedule}

**Definition: **When the equipment was last maintained.

**Format: **Free text.

### 7.16. Usage Levels

**Definition: **How often the piece of equipment is used.

**Format: **Free text.

### 7.17. Tolerance Class

**Definition: **The tolerance class of the piece of equipment.

**Format: **In accordance with [ISO
2768](https://www.plianced.com/compliance-wiki/iso-2768-general-geometrical-tolerances-and-technical-drawings/ "null").

### 7.18. Current Firmware

**Definition: **The current firmware used by the piece of equipment.

**Format: **Free text.

### 7.19. Uninterrupted Power Supply {#uninterrupted-power-supply}

**Defintion: **Whether the piece of equipment has an uninterrupted power
supply.

**Format: **TRUE / FALSE

### 7.20. Defined sub-properties 

These are specialised properties that only apply to specific types of
equipment. In this section th**e list of Equipment Properties provided
is extensible, and hasn't attempted to be exhaustive. The Equipment
sub-properties provided represent a significant proportion of equipment
used in manufacturing facilities. The below list of defined
sub-properties has been provided in alphabetical order for ease of use
and reference.**

#### 7.20.1. Axes

**Definition: **The number of axes.

**Format: **Integer.

#### 7.20.2. Bed Size

**Definition: **The bed size of a piece of equipment.

**Format: **Integer. Unit: mm.

#### 7.20.3. Bending Length

**Definition: **Length of bending.

**Format: **Integer. Unit: mm.

#### 7.20.4.Build Volume {#7204build-volume}

**Definition: **The dimensions of the build.

**Format: **Integer. Unit: mm\^3.

#### 7.20.5. Chuck Jaw Diameter

**Definition: **The diameter of the chuck jaw.

**Format: **Integer. Unit: mm.

#### 7.20.6. Collet Size

**Defintion: **The size of the collet.

**Format: **Integer. Unit: mm.

#### 7.20.7. Computer Controlled

**Definition: **Whether the equipment is computer controlled.

**Format: **TRUE / FALSE

#### 7.20.8. Cross Slide Travel

**Definition: **Distance of Cross Slide Travel.

**Format: **Integer. Unit: mm.

#### 7.20.9. Daylight / Opening

**Definition: **Daylight / Opening size.

**Format: **Integer. Unit: mm.

#### 7.20.10. Distance Between Centres

**Definition:** The distance between a centre in the headstock and a
centre in the tailstock.

**Format: **Integer. Unit: mm.

#### 7.20.11. Ejector Threads

**Definition: **Ejector Thread Size.

**Format:** Integer. Unit: mm.

#### 7.20.12. Extraction System

**Definition: **Is there an extraction system?

**Format: **TRUE / FALSE

#### 7.20.13. Gantry Material

**Definition: **The material the gantry is made out of.

**Format: **Uses [Material](https://standards.internetofproduction.org/pub/okw#materials-properties "null") class.

#### 7.20.14. Hot Runner Compatible

**Definition: **Whether the equipment is hot runner compatible.

**Format: **TRUE / FALSE

#### 7.20.15. Laser Power

**Definition: **Power consumption used.

**Format:** Integer. Unit: W.

#### 7.20.16. Layer Resolution

**Definition: **Thickness of layer.

**Format: **Integer. Unit: mm.

#### 7.20.17. Locating Ring Diameter

**Definition: **Diameter of the locating ring.

**Format: **Integer. Unit: mm.

#### 7.20.18. Material Worked

**Definition: **The type of material worked on the equipment.

**Format: **METAL / NON-METAL

#### 7.20.19. Maximum Clamping Force

**Definition: **The maximum clamping force of the equipment.

**Format:** Integer. Unit: t.

#### 7.20.20. Maximum Shot Volume

**Definition: **The maximum shot volume.

**Format: **Integer. Unit: mm\^3.

#### 7.20.21. Maximum Spindle Speed

**Definition: **The maximum spindle speed.

**Format:** Integer. Unit: rpm.

#### 7.20.22. Maximum Tie Bar Distance

**Definition: **The maximum tie bar distance.

**Format: **Integer. Unit: mm.

#### 7.20.23. Nozzle Size

**Definition: **Size of nozzle.

**Format: **Integer. Unit: mm.

#### 7.20.24. Nozzle Radius

**Definition: **Radius of the nozzle.

**Format:** Integer. Unit: mm.

#### 7.20.25. Optimal Material

**Definition: **The optimal material for use with a piece of equipment.

**Format: **Uses [Material](https://standards.internetofproduction.org/pub/okw#materials-properties "null") class.

#### 7.20.26. Pieceholding Type

**Definition: **How the part is fixed.

**Format: **Free text.

#### 7.20.27. Press Force

**Definition: **The press force.

**Format: **Integer. Unit: kN.

#### 7.20.28. Punch Force

**Definition: **The punch force.

**Format: **Integer. Unit: kN.

#### 7.20.29. Spindle Rotation

**Defintion: **The spindle rotation.

**Format: **Integer. Unit: Deg.

#### 7.20.30. Stations

**Definition: **The number of stations.

**Format: **Integer.

#### 7.20.31. Station size

**Definition: **The size of the station.

**Format: **Integer. Unit: mm.

#### 7.20.32. Tailstock Sleeve Travel

**Definition: **Distance of tailstock sleeve travel.

**Format: **Integer. Unit: mm.

#### 7.20.33. Tooling Type

**Definition:** The tooling type.

**Format: **Free text.

**Example: **Forming, Piercing.

#### 7.20.34. Turning Capacity / Swing

**Definition: **The turning capacity / swing of a piece of equipment.

**Format: **Integer. Unit: mm.

#### 7.20.35. Working Surface

**Definition: **The working surface of a piece of equipment.

**Format:** Integer. Unit: mm.

#### 7.20.36. X Travel

**Definition: **Distance of X travel.

**Format: **Integer. Unit: mm.

#### 7.20.37. Y Travel

**Definition: **Distance of Y travel.

**Format: **Integer. Unit: mm.

#### 7.20.38. Z Travel

**Definition: **Distance of Z travel.

**Format: **Integer. Unit: mm.


## 8. Materials Properties

This class incorporates properties relating to ƒwhat 3s. In general,
materials are outside of the scope for Open Know-Where, however a simple
standardised way of capturing materials is important. For instance, to
be able to use a manufacturing facility, a user needs to be aware of
what materials are available or commonly used at a specific location, or
to use a piece of equipment, a user will need to know what material the
machine is callibrated for. Materials are decisive facet of whether
something can be made at a specific manufacturing facility. 

Consequently, a simple standardised way of capturing materials is
provided by Open Know-Where, but future work to fully standardise
material classifications may be needed, and is currently being
investigated by the Internet of Production Alliance.

Where properties are logically grouped, they are presented as
collections of sub-properties. 

![](https://assets.pubpub.org/tum7vb24/41641401551202.png){#n08yscccr0n}

### 8.1. Manufacturer

**Definition: **The manufacturer of the material type.

**Format:** Free text.

### 8.2. Brand

**Definition: **The brand of the material type.

**Format: **Free text.

### 8.3. Supplier Location

**Definition: **Place of immediate supply to the facility.

**Format: **Use [Location](https://standards.internetofproduction.org/pub/okw#location-properties "null") class.

**Note: **This is not to be used for the location of the manufacturer of
the material, but where the facility gets the material from.

### 8.4. Material Type

**Definition: **Type of material.

**Format: **Provide the Wikiepedia URL for the relevant material type.

**Note: **For instructions how to do this, please see [section
3.5](https://standards.internetofproduction.org/pub/okw#how-do-i-use-the-classification-system "null").

### 8.5. Defined Material Types

In order to support interoperability across datasets, this section sets
out a standardised list of material types used in manufacturing.The list
is not intended to be exhaustive, but extensive enough to capture the
most common types of materials. 

In compiling the list, the level of specificity was deemed important. If
the list is too high-level, it  would not help a buyer or maker
determine if a facility is appropriate for their specific needs. If it
is too detailed a search could exclude equipment that could easily be
applied to similar materials. The figure below provides examples of the
level of specificity for different material types, which was used to
guide decision making in producing this list.

![](https://assets.pubpub.org/952oxiwk/21641401663620.png){#njqten8upzp}

Headings are included in the list to aid navigation by users of the
standard, but do not form part of the classification scheme and should
not be used in Open Know-Where datasets.

#### 8.5.1. Plastics

[HDPE](https://en.wikipedia.org/wiki/High-density_polyethylene "null")

[PLA](https://en.wikipedia.org/wiki/Polylactic_acid "null")

[ABS](https://en.wikipedia.org/wiki/Acrylonitrile_butadiene_styrene "null")

[PET](https://en.wikipedia.org/wiki/Polyethylene_terephthalate "null")

[Acetate](https://en.wikipedia.org/wiki/Cellulose_acetate "null")

[PVC](https://en.wikipedia.org/wiki/Polyvinyl_chloride "null")

[Nylon](https://en.wikipedia.org/wiki/Nylon "null")

[Polycarbonate](https://en.wikipedia.org/wiki/Polycarbonate "null")

[Polypropylene](https://en.wikipedia.org/wiki/Polypropylene "null")

[Acrylic](https://en.wikipedia.org/wiki/Acrylic "null")

#### 8.5.2. Metals

[Iron](https://en.wikipedia.org/wiki/Iron "null")

[Steel](https://en.wikipedia.org/wiki/Steel "null")

[Stainless Steel](https://en.wikipedia.org/wiki/Stainless_steel "null")

[Mild Steel](https://en.wikipedia.org/wiki/Carbon_steel "null")

[Galvanised
Steel](https://en.wikipedia.org/?title=Galvanized_steel&redirect=no "null")

[Aluminium](https://en.wikipedia.org/wiki/Aluminium "null")

[Copper](https://en.wikipedia.org/wiki/Copper "null")

[Zinc](https://en.wikipedia.org/wiki/Zinc "null")

#### 8.5.3. Wood Products

[Softwood](https://en.wikipedia.org/wiki/Softwood "null")

[Hardwood](https://en.wikipedia.org/wiki/Hardwood "null")

[MDF](https://en.wikipedia.org/wiki/Medium-density_fibreboard "null")

#### 8.5.4. Elastomers

[Natural Rubber](https://en.wikipedia.org/wiki/Natural_rubber "null")

[TPU ](https://en.wikipedia.org/wiki/Thermoplastic_polyurethane "null")

[Silicone](https://en.wikipedia.org/wiki/Silicone "null")

#### 8.5.5. Ceramics

[Geopolymers](https://en.wikipedia.org/wiki/Geopolymer "null")

[Ceramics](https://en.wikipedia.org/wiki/Ceramic "null")

[Clay](https://en.wikipedia.org/wiki/Clay "null")

#### 8.5.6. Electronics

[PCBs](https://en.wikipedia.org/wiki/Polychlorinated_biphenyl "null")

[Electronic
Components](https://en.wikipedia.org/wiki/Electronic_component "null")

#### 8.5.7. Others

[Textiles](https://en.wikipedia.org/wiki/Textile "null")

[Leather](https://en.wikipedia.org/wiki/Leather "null")

[Concrete](https://en.wikipedia.org/wiki/Concrete "null")

[Rock](https://en.wikipedia.org/wiki/Rock_(geology) "null")

[Soil](https://en.wikipedia.org/wiki/Soil "null")

[Composite
Materials](https://en.wikipedia.org/wiki/Composite_material "null")

[Food](https://en.wikipedia.org/wiki/Food "null")

[Compost](https://en.wikipedia.org/wiki/Compost "null")

[Resin](https://en.wikipedia.org/wiki/Resin "null")

[Glass](https://en.wikipedia.org/wiki/Glass "null")

[Carbon
Fiber](https://en.wikipedia.org/wiki/Carbon_fiber_reinforced_polymer "null")

[Cardboard](https://en.wikipedia.org/wiki/Cardboard "null")

[Paper](https://en.wikipedia.org/wiki/Paper "null")

## 9. Record Data Properties

This class incorporates properties relating to record data. By "record
data" we mean information about who created the data and how up to date
it is. In highly dynamic environments, datasets can quickly become
obsolete and so it can be helpful to share information about the
provenance of the data.

![](https://assets.pubpub.org/yrp7hctn/51641401818620.png){#n8qz3t4kmpp}

### 9.1. Date Created

**Defintion: **Date record was created.

**Format: **Recommended practice is to use [ISO
8601](https://www.iso.org/iso-8601-date-and-time-format.html "null"),
i.e the format `YYYY-MM-DD`.

### 9.2. Created By

**Definition:**[Agent](https://standards.internetofproduction.org/pub/okw#agent-properties "null") who
created the resource.

**Format: **Use [Agent](https://standards.internetofproduction.org/pub/okw#agent-properties "null") class.

### 9.3. Last Updated

**Definition: **Date the record was updated.

**Format: **Recommended practice is to use [ISO
8601](https://www.iso.org/iso-8601-date-and-time-format.html "null"),
i.e the format `YYYY-MM-DD`.

### 9.4. Updated By

**Defintion: **The Agent who updated the record.

**Format: **Use
the [Agent](https://standards.internetofproduction.org/pub/okw#agent-properties "null") class.

### 9.5. Date Verified

**Definition: **Date the data in the record was verified.

**Format: **Recommended practice is to use [ISO
8601](https://www.iso.org/iso-8601-date-and-time-format.html "null"),
i.e. the format `YYYY-MM-DD`.

### 9.6. Verified By

**Defintion: **The agent who verified the data in the record.

**Format: **Use
the [Agent](https://standards.internetofproduction.org/pub/okw#agent-properties "null") class.