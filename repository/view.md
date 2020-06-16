# View Repository

As a User, I would like a page about the Repository in the Public User Interface, so that I can learn more about the Repository and its Collections without looking at a more specific Object.

References: [CHO-739](https://github.com/psu-libraries/cho/issues/739)

## CONTENTdm

[University Libraries Digital Collections](https://digital.libraries.psu.edu)

## It should

- [ ] Pass accessibility tests
- [ ] Be responsively designed ([CHO-138](https://github.com/psu-libraries/cho/issues/138))
- [ ] Emphasize discovery
- [ ] Have 0 to 1 blocks of contextual description ("Digital Collections is... ")
- [ ] Display useful error messages ([CHO-129](https://github.com/psu-libraries/cho/issues/129))
    * In CONTENTdm, error messages are configurable in the Website Configuration Tool, if one has administrative privileges. They must be set globally in the cdmLanguage.xml file, available under Localizations; the configuration changes must be published after they are uploaded. Uncertain if they can be set by collection (thereby allowing users to contact specific collection owners or curators if they have further questions about an error). Also, the number of errors with specific error message is somewhat limited; there are probably a lot of things where we would need to contact OCLC for further information, if encountered by a user.

## Benchmarks

* [NYPL](https://digitalcollections.nypl.org)
* [Duke](https://repository.duke.edu/dc?)
* [Oregon Digital](https://oregondigital.org/catalog)
* [UCSD](https://library.ucsd.edu/dc)
