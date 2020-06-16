Still haven't found a good way to track user stories, functional requirements, and UX testing notes. I'm pretty sure this repository isn't it but I'll give it a shot again before I try something else.

## First principles

([templates for including these in user stories](it-should.md))

The Repository and all of its content should comply with [WCAG 2.0](https://www.w3.org/TR/WCAG20) and [Section 508](https://en.wikipedia.org/wiki/Section_508_Amendment_to_the_Rehabilitation_Act_of_1973) accessibility standards, as documented by VPAT and/or by accessibility testing. ([Request a CONTENTdm VPAT](https://help.oclc.org/Metadata_Services/CONTENTdm/Troubleshooting/How_do_I_receive_a_copy_of_the_CONTENTdm_VPAT))

The Repository and all of its content should be responsively designed.

The Repository and its contents should be represented by persistent URLs, in line with a broader University Libraries-level strategy for uniquely identifying its digital assets. ([CHO-22](https://github.com/psu-libraries/cho/issues/22), [CHO-132](https://github.com/psu-libraries/cho/issues/132), [CHO-133](https://github.com/psu-libraries/cho/issues/133), [CHO-164](https://github.com/psu-libraries/cho/issues/164))

The Repository and its contents should be represented by UUIDs native to the Repository itself. ([CHO-64](https://github.com/psu-libraries/cho/issues/64))

## Design considerations

Open questions about the services included in the Repository.

Should the Repository serve both preservation and access use cases, or should it be limited only to access (with preservation happening elsewhere, with its own user stories)?

How should we allow for batch metadata editing in the Repository? Should it be built into the Administrative User Interface itself, or should Metadata Specialists use outside metadata editing tools (Excel, OpenRefine, MarcEdit, etc.) to limit the chance of inadvertent bulk changes to Work metadata?

## Miscellany

The following are user stories from CHO that would be nice to have, but don't seem to be core Repository functions. They are ordered roughly by how easy they would be to implement in production, according to me, having done absolutely no consultation with anyone else about it.

* **[Initiate contact with library](https://github.com/psu-libraries/cho/issues/202)** A link to contact the library with questions about the Repository or its Objects. Could contact specific people based on the Collection being viewed (i.e. know who the Curator is and direct the e-mail to that person), but at minimum should e-mail the Repository product owner so that they may direct the question to the appropriate contact.
* **[Serendipity button](https://github.com/psu-libraries/cho/issues/53)** A link that would take you to a random Work in the Repository.
* **[Canvas integration](https://github.com/psu-libraries/cho/issues/51)** Integrate the display of Repository Works in Canvas. Possible with Universal Viewer embed codes. May happen as a side effect of fulfilling other user stories.
* **[Photomosaic visualization of Repository Work images](https://github.com/psu-libraries/cho/issues/75)** So that we could do a carousel-type thing with images from the Repository or specific Collections. Curatorial role. Not core to the Repository, but valuable for high-impact stakeholders (deans and directors, etc.)
* **[User downloads to cloud storage](https://github.com/psu-libraries/cho/issues/36)** Let a User download a Work or set of Works directly to their personal cloud storage. Not MVP; the Repository doesn't need to be prescriptive about this.
* **[Push ARK links to ArchivesSpace](https://github.com/psu-libraries/cho/issues/197)** When an ARK is minted for an archival resource, push that link to the ArchivesSpace record representing that resource. Preservation application use case?
* **[Checksumming when moving files across servers](https://github.com/psu-libraries/cho/issues/228)** Regenerate checksums when a file gets moved. Preservation application use case?
