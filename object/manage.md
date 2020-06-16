# Manage Object

## It should

- [ ] Pass accessibility tests
- [ ] Be responsively designed ([CHO-138](https://github.com/psu-libraries/cho/issues/138))
- [ ] Allow Collection membership to be edited ([CHO-539](https://github.com/psu-libraries/cho/issues/539))
- [ ] Allow Files to be added ([CHO-359](https://github.com/psu-libraries/cho/issues/359))
- [ ] Allow File Sets to be edited ([CHO-633](https://github.com/psu-libraries/cho/issues/633)) (if File Sets are required for the repository)
- [ ] Allow thumbnails to be customized ([CHO-169](https://github.com/psu-libraries/cho/issues/169))
- [ ] Allow for mediated Object creation and management:
    - [ ] Submission ([CHO-94](https://github.com/psu-libraries/cho/issues/94))
    - [ ] Searching the mediation queue ([CHO-95](https://github.com/psu-libraries/cho/issues/95))
    - [ ] Viewing the mediation queue in table form ([CHO-96](https://github.com/psu-libraries/cho/issues/96))
    - [ ] Editing items in the mediation queue ([CHO-222](https://github.com/psu-libraries/cho/issues/222))
    * CONTENTdm uses the Approval Queue in Project Client for this. Any repository we use should have similar functionality.
- [ ] Allow a work to belong to multiple Collections ([CHO-59](https://github.com/psu-libraries/cho/issues/59))
- [ ] Allow objects to be deleted ([CHO-119](https://github.com/psu-libraries/cho/issues/119), [CHO-192](https://github.com/psu-libraries/cho/issues/192) (for nested works), [CHO-509](https://github.com/psu-libraries/cho/issues/509))
    * What to do when objects are deleted? Should the URI and UUID return "tombstones," HTTP status code 410, nothing at all? See [CHO-166](https://github.com/psu-libraries/cho/issues/166)
- [ ] Allow files and file sets to be deleted ([CHO-297](https://github.com/psu-libraries/cho/issues/297), [CHO-638](https://github.com/psu-libraries/cho/issues/638))
- [ ] Restrict Objects from public display ([CHO-88](https://github.com/psu-libraries/cho/issues/88))
- [ ] Edit objects in place, e.g. to do simple image edits such as rotating ([CHO-150](https://github.com/psu-libraries/cho/issues/150)), or re-ordering components of a compound object ([CHO-151](https://github.com/psu-libraries/cho/issues/151))

## It would be nice if it could

- [ ] Create or derive technical metadata on ingest, such as checksums ([CHO-68](https://github.com/psu-libraries/cho/issues/68)) and MIME types ([CHO-69](https://github.com/psu-libraries/cho/issues/69), [CHO-167](https://github.com/psu-libraries/cho/issues/167))
    * Checksums may be the responsibility of the preservation application; we would use integrations for this
- [ ] Replace File Sets ([CHO-117](https://github.com/psu-libraries/cho/issues/117))
- [ ] Support WARC (Web archives) as Work Types ([CHO-201](https://github.com/psu-libraries/cho/issues/201))
    * At minimum, as bitstreams; at maximum, with viewing/emulation support.
- [ ] Export BagIt bags ([CHO-441](https://github.com/psu-libraries/cho/issues/441))
- [ ] Save incomplete works (e.g. metadata without objects; metadata lacking all required properties) ([CHO-97](https://github.com/psu-libraries/cho/issues/97))
- [ ] Save in background while work is in progress ([CHO-188](https://github.com/psu-libraries/cho/issues/188))
- [ ] Have configurable options for file names upon download ([CHO-440](https://github.com/psu-libraries/cho/issues/440))
- [ ] Embed descriptive metadata into service files ([CHO-77](https://github.com/psu-libraries/cho/issues/77))
- [ ] Provide one-time access to restricted Objects ([CHO-144](https://github.com/psu-libraries/cho/issues/144))
- [ ] Generate high-quality service files on ingest ([CHO-152](https://github.com/psu-libraries/cho/issues/152))
    * This may be something that happens offline, in the preservation repository.
- [ ] Support Structured Nested Works ([CHO-61](https://github.com/psu-libraries/cho/issues/61))
    * From the glossary: a Structured Nested Work is "a Nested Work with arbitrarily deep hierarchical structure, such as a book or a born-digital archival collection, containing Components that determine how the Work is to be organized for curation and presentation to a User. Examples of a Structured Nested Work include a book, scholarly journal, or born-digital archival collection with built-in arrangement structure."
    * It may be worth deconstructing what exactly we need Structured Nested Works to do, if other repositories may suit the use case better (such as OJS for journals), and if we can slowly build this capacity up through other user stories.
