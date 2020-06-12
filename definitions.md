Definitions of content classes in the Repository are linked to their close-matched terms in the [Portland Common Data Model](https://github.com/duraspace/pcdm/wiki/PCDM-2.0), when possible.

**Administrative User Interface** The mechanism, mediated via Web browser, whereby Administrators, Curators, and Metadata Specialists interact with the Repository and its constituent Works for the purpose of creating, updating, and/or deleting those Works. For example, in CONTENTdm, this may be the Project Client or the [CONTENTdm Administration site](https://server17287.contentdm.oclc.org/cgi-bin/admin/start.exe).

**Authenticated User** A User with specific permissions to perform one or more Curation Activities on the Repository or a subset of its Objects. An Authenticated User may have one or more of the following User roles within the Repository, or a set of Objects:

* **Administrator** A User with the ability to perform all Curation Activities throughout the Repository
* **Curator** A User with the ability to perform some or all Curation Activities only for Objects for which permissions have been assigned by an Administrator, according to shared collection development policies and protocols
* **Metadata Specialist** A User with the ability to create, update, or delete metadata properties and values for any Collection or Work, or for a subset of Objects for which permissions have been assigned by an Administrator according to shared collection development policies and protocols

**Collection** A curated group of one or more Works sharing similar characteristics, such as topical theme, geography, form, or provenance. A Collection may be Managed (created by an Authenticated User for the primary purpose of managing Works according to a collection development policy) or Curated (created by any user for any purpose). ([pcdm:Collection](https://github.com/duraspace/pcdm/wiki/PCDM-2.0#pcdmcollection--oreaggregation))

**Component** The constituent part(s) of a Work; a single image representing an artwork or digitized book, a single digitized cassette tape from a larger oral history sound recording, etc. A Component is represented by a single Fileset. ([pcdm:Object](https://github.com/duraspace/pcdm/wiki/PCDM-2.0#pcdmobject--oreaggregation))

**Curated Collection** A Collection created by any User for any purpose, consisting of Works which are primarily stewarded in an existing Managed Collection. Curated Collections may be used to coordinate research or instruction, to allow for batch updates to existing Works, or to create exhibits featuring Repository content.

**Curation Activity** An action taken by a User in order to facilitate stewardship of the Repository or its constituent Objects. Includes creating, updating, or deleting files, metadata, and/or resource relationships covering Objects in the Repository.

**File** A binary stream representing a part of a Work. This may include a direct representation of the Work itself; service files used for easier access to the Work; transcripts; metadata; or other supplementary materials to aid in interpreting the Work. A File may belong to only one Fileset. ([pcdm:File](https://github.com/duraspace/pcdm/wiki/PCDM-2.0#pcdmfile))

In the [Digital Object Guidelines](https://git.psu.edu/digipres/documentation/blob/master/digitalObjectGuidelines/guidelines.md), Files may be one of the following types:

* **\_preservation** preservation master (master preservation file, e.g. tiff, wav, avi)
* **\_preservation-redacted** redacted preservation master, for PII or other sensitive material
* **\_service** service master, access master (master service file for viewers, e.g. jp2, dv)
* **\_access** access derivative for user download (e.g. pdf, jpg)
* **\_thumb** display thumbnail
* **\_text** plain text, transcription, OCR output
* **\_caption** time-coded captions for a media file (e.g. vtt, srt)
* **\_media** images of the original physical media or housing, to be included when digitizing time-based media. Prepend additional descriptors as necessary, including but not limited to:
    * \_front\_media
    * \_back\_media
    * \_housing\_media

**Fileset** The Files which, taken together, represent a Component of a Work. ([pcdm:Fileset](https://github.com/duraspace/pcdm/wiki/PCDM-2.0#pcdmfileset--oreaggregation))

> The general idea here, which for now I will phrase in VRA terminology, is that a Work consists of one or more Images. It's the Images which, in PCDM terms, represent the Object with which a Fileset is associated. This will become clearer (hopefully!) once this document more strictly defines things like compound objects, nested works, and other complicated classes of Works that exist in the Repository.

**Managed Collection** A Collection created by a Curator for the primary purpose of managing Works according to a collection development policy. A Work must belong to at least one Managed Collection.

The [Digital Object Guidelines](https://git.psu.edu/digipres/documentation/blob/master/digitalObjectGuidelines/guidelines.md) distinguish between Archival Collections (those described as record groups in ArchivesSpace) and Library Collections (those described at the item level in the library catalog).

**Nested Work** A Work containing more than one Component, such as a 3-D object represented from multiple views, or a diary whose pages each carry their own description and transcripts.

**Object** The base class in the Repository for all content types. Objects may be Collections, Works, Files, or Filesets. All Objects will be assigned an identifier.

**[Public User](https://github.com/psu-libraries/cho/issues/447)** A User interacting with a Collection or Work in the Repository without intent to change it, for purposes of research, scholarship, or instruction. A Public User has not been assigned permissions for Curation Activities, or is not logged into the Repository to perform them. Interacts with the Repository through the Public User Interface only.

**Public User Interface** The mechanism, mediated via Web browser, whereby Public Users interact with the Repository and its constituent Works, without expectation that those Works will be changed in any way. For example, in CONTENTdm, this would be the [Digital Collections home page](https://digital.libraries.psu.edu/digital).

**Repository** A sociotechnical platform or application for managing and presenting content, organized around Collections and maintained by Users, and developed around a shared set of policies and protocols.

**Structured Nested Work** A Nested Work with arbitrarily deep hierarchical structure, such as a book or a born-digital archival collection, containing Components that determine how the Work is to be organized for curation and presentation to a User. Examples of a Structured Nested Work include a book, scholarly journal, or born-digital archival collection with built-in arrangement structure.

**User** An individual performing an action (e.g. viewing, creating, updating, or deleting) within the Repository or within one of its constituent Objects. A User may be Public (i.e. not authorized for Curation Activities or not authenticated to perform Curation Activities) or Authenticated (i.e. is logged into the Repository and may perform Curation Activities).

**User Story** A documented need, held by one or more classes of User, for which Repository functionality is developed.

**Work** A single object of scholarly or cultural heritage content contained within the Repository. May belong to one or more Collections. A Work must primarily belong to a Managed Collection, but may have secondary memberships in Collections of either type. A Work consists of one or more Components. ([pcdm:Object](https://github.com/duraspace/pcdm/wiki/PCDM-2.0#pcdmobject--oreaggregation))

**Work Type** A classification of a Work, defined by an Administrator or Curator, to which a set of metadata properties and display rules are assigned to dictate how that Work is presented to Users. Work Types are often format-based, such as Image, Audio, Video, 3-D Object, or Geospatial.
