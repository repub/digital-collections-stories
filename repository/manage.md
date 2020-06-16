# Manage Repository

As an Authenticated User, I would like a personalized Repository dashboard in the Administrative User Interface, so that I can quickly access the Curation Activities that are available to me. ([CHO-788](https://github.com/psu-libraries/cho/issues/788))

## Benchmarks

In CONTENTdm: Project Client, Administrative User Interface

## It should

- [ ] Support static pages ([CHO-288](https://github.com/psu-libraries/cho/issues/288))
    * Not sure what static pages are required, but could include things like collections policy, takedown requests, information about requesting reproductions, and so on. Could be native to the repository or part of a Web presence in Drupal or other CMS.
- [ ] Automatically re-index the repository on changes ([CHO-193](https://github.com/psu-libraries/cho/issues/193))
    * In CONTENTdm this is a manual process which must be done by a user before changes take effect in the index.
- [ ] Support Work Types ([CHO-320](https://github.com/psu-libraries/cho/issues/320))
- [ ] Support Universal Viewer ([CHO-187](https://github.com/psu-libraries/cho/issues/187))
    - [ ] Viewing books ([CHO-46](https://github.com/psu-libraries/cho/issues/46))
    - [ ] Viewing videos ([CHO-47](https://github.com/psu-libraries/cho/issues/47))
    - [ ] Listening to audio ([CHO-48](https://github.com/psu-libraries/cho/issues/48))
        * We could look at Kaltura integration for A/V content ([CHO-569](https://github.com/psu-libraries/cho/issues/569); also see [UW-Milwaukee's CONTENTdm/Kaltura integration](https://collections.lib.uwm.edu/digital/collection/march/id/1747/rec/2))
    - [ ] Viewing three-dimensional objects ([CHO-70](https://github.com/psu-libraries/cho/issues/70))
    - [ ] Viewing compound objects using paging ([CHO-49](https://github.com/psu-libraries/cho/issues/49))
- [ ] Support internationalization ([CHO-163](https://github.com/psu-libraries/cho/issues/163) (for public user interface), [CHO-378](https://github.com/psu-libraries/cho/issues/378))
- [ ] [Allow gathering of usage statistics](https://git.psu.edu/kmc35/digital-collections/-/issues/114)
- [ ] [Allow reports](https://git.psu.edu/kmc35/digital-collections/-/issues/115)
- [ ] Support large files (so that they do not need to be managed separately in Isilon storage) ([CHO-210](https://github.com/psu-libraries/cho/issues/210))
- [ ] Support easier editing of Objects from large Collections than is possible with CONTENTdm ([CHO-194](https://github.com/psu-libraries/cho/issues/194), [CHO-203](https://github.com/psu-libraries/cho/issues/203))

## It would be nice if it could

- [ ] Support hosting of Collection-level administrative documentation ([CHO-351](https://github.com/psu-libraries/cho/issues/351))
    * These would be things like MOUs with project partners, deeds of gift, donor files, embargoes limiting how widely a Collection and its Works may be distributed, etc. They would be uploaded and described as Works, but would be likely need to be their own Work Type so that we can assign them their own metadata template, restrict them to Authenticated Users, etc.
- [ ] Allow Administrators the option of making preservation copies of a file available for download ([CHO-205](https://git.psu.edu/kmc35/digital-collections/-/issues/205))
- [ ] Allow file versioning ([CHO-162](https://github.com/psu-libraries/cho/issues/162))
- [ ] Display curation activity streams, similar to GitHub issues ([CHO-790](https://github.com/psu-libraries/cho/issues/790))
- [ ] Notify users when new Objects are published ([CHO-200](https://github.com/psu-libraries/cho/issues/200)) (Using a JSON update feed? E-mail notifications? Other?)
