---
xZINECOREx Schema Scope Notes
-----------------------------

*This scope notes document serves to define the schema fields in a
human-readable way.*

**ZineCore Label/Field**
 - *All fields are repeatable unless otherwise noted*
 - *Required fields that have no data will indicate that*

- **Alternative Title(s)**
   - Secondary titles or subtitles

- **Title**
  -  Title of zine - required field
  -  *field not repeatable*

- **Creator(s)**
  - Creator of zine - *this will refer to an actual person or institution*
  	required field

- **Subjects(s)**
  - name/topic of material
  - will have controlled vocabulary
    - LCSH
    - Anchor Archive Zine Catalog
    - Possible Zine Union Catalog internal vocabulary TBD?

- **Description and Notes** - *Has four subfields as defined below*
  - **Genre(s)** - Genre terms help to explain both the content of the work (e.g. bikezine or perzine) and/or the form of the work (e.g. 24-hour zine or one-page-folded zine)
  - **Abstract** - Abstract is a brief summary of the contents of the zine.
  - **Table Of Contents** - Lists the contents of the zine
  - **Public Notes** - Notes that will get shared with the Zine Union Catalog.  Institutions may also keep internal notes that do not get shared publicly.
        
- **Provenance**
  - Where the zine came from. Example: Donated by the creator OR was part of *n* collection OR 'Purchased at Quimby's.' *No. 3 donated by Keight Bergmann in 2011*
  - Shows path of how zine came to your collection.
  - May or may not be used in the zine union catalog.

- **Publisher(s)/Press**
  - not required but when used will be associated with a controlled vocabulary

- **Contributor(s)**
  - will refer to people (usually humans, felines and cephalopods but by no means is that exhaustive) other than the creator who contributed to the zine. May also include subjects of interviews, reviews, etc.
  - Revision to this field forthcoming (05.16.15)
   
- **Date Created**
  - Human readable date. I.e. 1996 or April 4, 1968
  - *Required Field*

- **Date**
  - Machine-readable date. SEE  http://www.w3.org/TR/NOTE-datetime
  - *Required Field*
        
- **Format** - *Has three subfields as defined below*
  - Physical dimensions - Height and width of document (in mm?) *controlled vocab?*
  - Number of Pages -  the number of pages in the zine
  - Medium - describes printing process, materials, binding and other physical properties

- **Identifier(s)**
  - Union ID - Canonical UID and URI of the zine in the Union Catalog
  - Internal ID - URI or ID number associated with individual institutions
  - *field not repeatable*

- **Source**
  - A related resource from which the described resource is derived. Example: A digitized copy of a zine is sourced from the original printed version.
  - This will be individualized to your specific institution.

- **Language**
  - The language(s) that the zine was published in
  - Has controlled vocabulary ISO 639-1. SEE http://www-01.sil.org/iso639-3/codes.asp
    - Recognize that this is a robot-centric decision to conform to all the various pieces of code that use this
  - *Required Field*

- **Relation** *(see also)*
  - we can use the refinement: RELATION>>IS PART OF and call it COLLECTION
  - we can use the refinement RELEATION>>IS PART OF and call it SERIES
  - we can use the refinement RELATION>>HAS PART in many ways, 2 important elements might be: VOLUME and ISSUE
  - Most "See Also" references in databases are based on subjectality or aboutness.  This "See Also" functionality is built using a theasurus or standard vocabulary and coding on the backend of the database.
Example of a zine controlled vocabulary: Anchor Archive Zine Thesaurus: http://www.robertsstreet.org/thesaurus/out.htm 
You could easily build "See Also" references based on the relationships defined in this thesaurus.

- **Coverage** *(place of publication)*
  - refinement COVERAGE>>LOCATION to be where something was published.
  - when a zine is about a place, that is a subject heading (of some sort)
  - when a zine is about traveling to a place, then it should have "travel zine" as a genre term
  - *Required Field*

- **Rights** *(freedoms and restrictions)*
  - Comes from the creator or item.
  - Can include Copyright ©, but also copyleft, anti-copyright, freely duplicatable, Creative Commons or other license.
  - Not required
