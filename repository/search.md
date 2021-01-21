# Search Repository

As a User, I would like the ability to search the Repository, so that I can find Objects that are of interest to me in my research, scholarship, or instruction.

## It should

- [ ] Pass accessibility tests
- [ ] Be responsively designed ([CHO-138](https://github.com/psu-libraries/cho/issues/138))
- [ ] Allow for searching on the following parameters ([CHO-39](https://github.com/psu-libraries/cho/issues/39)):
    - [ ] Form or Work Type ([CHO-11](https://github.com/psu-libraries/cho/issues/11))
    - [ ] File name ([CHO-122](https://github.com/psu-libraries/cho/issues/122))
        * Should tokenize underscores and periods in indexer ([CHO-729](https://github.com/psu-libraries/cho/issues/729))
    - [ ] Geospatial aspects:
        - [ ] Geographic point coordinates ([CHO-109](https://github.com/psu-libraries/cho/issues/109))
        - [ ] Geographic range/area ([CHO-110](https://github.com/psu-libraries/cho/issues/110))
    * A user should be able to easily switch between basic and advanced search ([CHO-41](https://github.com/psu-libraries/cho/issues/41))
- [ ] [Filter search results](https://git.psu.edu/kmc35/digital-collections/-/issues/15)
    - [ ] Filter by EDTF date ([CHO-33](https://github.com/psu-libraries/cho/issues/33), [CHO-723](https://github.com/psu-libraries/cho/issues/723), [CHO-724](https://github.com/psu-libraries/cho/issues/724), [CHO-725](https://github.com/psu-libraries/cho/issues/725))
    - [ ] Filter by collection or object restrictions (closed, restricted to PSU community, metadata-only)
        * Per reference question received 2020-06-29
        * Also came up several times in the first round of UX testing
- [ ] Limit searches by Collection ([CHO-9](https://github.com/psu-libraries/cho/issues/9), [CHO-10](https://github.com/psu-libraries/cho/issues/10) (across collections))
- [ ] Sort results:
    - [ ] By Collection ([CHO-128](https://github.com/psu-libraries/cho/issues/128))
- [ ] Allow an administrator to configure metadata to be displayed in search result summaries ([CHO-105](https://github.com/psu-libraries/cho/issues/105))
- [ ] Display Collection-Object relationships ([CHO-134](https://github.com/psu-libraries/cho/issues/134))
- [ ] Allow for searching/browsing by controlled vocabulary values ([CHO-127](https://github.com/psu-libraries/cho/issues/127))
- [ ] Only display parent-level images of compound objects in search result summary ([CHO-78](https://github.com/psu-libraries/cho/issues/78))
    * This user story came from VRC and has to do with their architecture collections, where "objects" represent buildings with images of multiple views, where the "parent-level image" might be curated (as opposed to things like books, where it's mostly okay for the image to be the cover or the first page).

## It would be nice if it could

- [ ] Display related search results ([CHO-111](https://github.com/psu-libraries/cho/issues/111)) (Relate on: subject, collection, author, time period, etc.)
- [ ] Display excerpts of text or metadata with search query highlighted, in search result summary ([CHO-156](https://github.com/psu-libraries/cho/issues/156))
- [ ] Display key metadata values on hovering over a thumbnail in search results (in grid view), to assess whether to click through to an object ([CHO-185](https://github.com/psu-libraries/cho/issues/185))
