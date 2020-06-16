# Manage Metadata

Services to allow a Metadata Specialist to maintain descriptive, technical, and administrative information about the Repository and its Collections and Objects.

## Benchmarks

* Cross-repository metadata templates ([CHO-15](https://github.com/psu-libraries/cho/issues/15))
    * [Base Metadata Application Profile (MAP) for CONTENTdm](https://psu.app.box.com/file/211247382460) (links to Box)
* Minimum viable description; core set of properties ([CHO-322](https://github.com/psu-libraries/cho/issues/322))
* Technical metadata ([CHO-66](https://github.com/psu-libraries/cho/issues/66))
* Administrative metadata ([CHO-66](https://github.com/psu-libraries/cho/issues/66))

## It should

- [ ] Allow a Metadata Specialist to configure brief and full metadata displays at the Work Type level ([CHO-484](https://github.com/psu-libraries/cho/issues/484))
- [ ] Allow assignment of roles when relating Agents with the Collection or Object for which they bear responsibility ([CHO-87](https://github.com/psu-libraries/cho/issues/87))
    * This is phrased as "Creator Roles" but could also be used to assign responsibility for management of objects in the repository, as well
    * "Creator Role" would likely be associated with a controlled vocabulary, such as the [MARC Relator Terms](https://www.loc.gov/marc/relators/relaterm.html). You could pair it with a creator name in the data model by making "Creator" (or "Linked Agent", as ArchivesSpace calls it) an array containing key/value pairs for Name and Role.
- [ ] Display tooltips or other property-specific guidance for entering metadata values ([CHO-54](https://github.com/psu-libraries/cho/issues/54))
- [ ] Batch import (from CSV, XML) ([CHO-20](https://github.com/psu-libraries/cho/issues/20), [CHO-67](https://github.com/psu-libraries/cho/issues/67), [CHO-207](https://github.com/psu-libraries/cho/issues/207))
- [ ] Batch export (to CSV, XML) ([CHO-17](https://github.com/psu-libraries/cho/issues/17))
    * Include File Set metadata ([CHO-650](https://github.com/psu-libraries/cho/issues/650))
- [ ] Allow batch find/replace (_in situ_ or using OpenRefine?) ([CHO-28](https://github.com/psu-libraries/cho/issues/28), [CHO-106](https://github.com/psu-libraries/cho/issues/106))
- [ ] Allow for local metadata properties that do not align or map to established metadata vocabularies ([CHO-102](https://github.com/psu-libraries/cho/issues/102))
- [ ] Encode metadata using UTF-8 ([CHO-93](https://github.com/psu-libraries/cho/issues/93))
    * Sanitize form inputs
- [ ] Have metadata templates at the Work Type level (e.g. Text, Cartographic, A/V) ([CHO-57](https://github.com/psu-libraries/cho/issues/57))
- [ ] Manage controlled vocabularies ([CHO-5](https://github.com/psu-libraries/cho/issues/5), [CHO-18](https://github.com/psu-libraries/cho/issues/18) (local vocabularies))
- [ ] Allow for a metadata property to have multiple values assigned to it ([CHO-98](https://github.com/psu-libraries/cho/issues/98))
- [ ] Support EDTF encoding of dates ([CHO-267](https://github.com/psu-libraries/cho/issues/267))
    - [ ] Display human-readable strings of EDTF-encoded dates ([CHO-687](https://github.com/psu-libraries/cho/issues/687))
- [ ] Allow for contextual information about archival objects ([CHO-25](https://github.com/psu-libraries/cho/issues/25))
- [ ] Record legacy identifiers (e.g. PURLs and/or CONTENTdm identifiers) ([CHO-160](https://github.com/psu-libraries/cho/issues/160))
- [ ] Record collection-level metadata ([CHO-161](https://github.com/psu-libraries/cho/issues/161))
- [ ] Serialize metadata according to multiple schema (MARC, MODS, etc.) ([CHO-99](https://github.com/psu-libraries/cho/issues/99) (for "standard" schema), [CHO-232](https://github.com/psu-libraries/cho/issues/232) (for "additional" schema))
- [ ] Report on the values assigned to a metadata property ([CHO-29](https://github.com/psu-libraries/cho/issues/29))

## It would be nice if it could

- [ ] Support version control ([CHO-37](https://github.com/psu-libraries/cho/issues/37))
- [ ] Store codes and display text separately, e.g. "eng" and "English" for Language ([CHO-104](https://github.com/psu-libraries/cho/issues/104))
- [ ] Link to external controlled vocabularies ([CHO-19](https://github.com/psu-libraries/cho/issues/19))
    * Apply controlled vocabulary terms (from LCSH, Getty, etc.) without needing to manage them _in situ_
    * Include URIs in display labels on Collection or Object edit
- [ ] Support Markdown formatting of metadata values ([CHO-214](https://github.com/psu-libraries/cho/issues/214))
- [ ] Import metadata from ArchivesSpace ([CHO-142](https://github.com/psu-libraries/cho/issues/142))
- [ ] Import metadata from MARC/the catalog ([CHO-157](https://github.com/psu-libraries/cho/issues/157))
- [ ] Batch import Agents (name authority records) ([CHO-737](https://github.com/psu-libraries/cho/issues/737))
    * Will need to decide if Agents are a first-class object in the repository, similar to Collections and Objects
- [ ] Allow local controlled vocabularies to be edited while updating Objects ([CHO-191](https://github.com/psu-libraries/cho/issues/191))
- [ ] Globally re-assign certain metadata values to a new metadata property ([CHO-55](https://github.com/psu-libraries/cho/issues/55))
- [ ] Re-associate metadata with different Objects, files, and/or filesets ([CHO-123](https://github.com/psu-libraries/cho/issues/123))
- [ ] Implement RDF ontologies in the data dictionary ([CHO-285](https://github.com/psu-libraries/cho/issues/285))
- [ ] Allow for additional metadata syndication formats beyond OAI-PMH ([CHO-286](https://github.com/psu-libraries/cho/issues/286), maybe also [CHO-159](https://github.com/psu-libraries/cho/issues/159))
- [ ] Allow administrators and metadata specialists to edit Solr indexing synonyms in the Administrative User Interface ([CHO-206](https://github.com/psu-libraries/cho/issues/206))
- [ ] Restrict users to a subset of terms in a controlled vocabulary, to allow for better quality control and to train students and new metadata specialists on how to describe objects ([CHO-89](https://github.com/psu-libraries/cho/issues/89)) (This seems... difficult to enforce)
