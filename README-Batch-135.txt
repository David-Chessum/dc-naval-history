Batch 135 - 11 November 2026

Deployment instructions
1. Back up matching files in the website repository.
2. Extract this ZIP and copy its seven HTML/JavaScript files into the website root, replacing matching files. README is for reference only.
3. Commit and push to the main branch using your normal GitHub Desktop process. Retain all other website files and assets.
4. Wait for the new Pages workflow to succeed. Website batch numbers and GitHub workflow run numbers are different.
5. Refresh the changed pages and Search with Ctrl+F5. Check the new DBFP panel, page and update links; publication links; filters and both pagination bars.

Changes incorporated
- Created Documents on British Foreign Policy using the FRUS layout, with supplied introduction, all 65 entries across four series and 50 complete volume links. The incomplete supplied Series 1A Volume 3 link remains unlinked. Source wording is retained.
- Added title filtering, 50 entries per page by default, and synchronised First/Previous/page indicator/Next/Last pagination above and below the DBFP table. Removed the Sort by control as requested.
- Added the linked DBFP panel immediately after FRUS on the Naval History Document Archive page.
- Added the 11 November 2026 DBFP Recent Updates entry with the requested wording.
- Added the DBFP home-page update and removed the fifth item, the Swedish Pensacola proposal, retaining five items.
- Linked five existing Admiralty publication titles: CB 4273 (52), East of Malta / West of Suez, Fleet Air Arm, His Majesty's Submarines and The Battle of the River Plate.
- Added five linked NN publications alphabetically: Ark Royal (1942), British Merchantmen at War (1944), Ocean Front (1945), The Battle of the Atlantic (1946) and The Town Class Destroyers (1949), all with TNA Ref Not found.
- Set the 1944 Mediterranean Fleet / Greece to Tripoli entry's TNA Ref to Not found.
- Replaced Admiralty Publications pagination with DBFP-style synchronised controls above and below its table.
- Refreshed comprehensive search to v105: 325 pages and 57,367 table records. Existing search implementation, including duplicate-result handling, is preserved.

Validation
ZIP CRC and extracted byte checks passed. Inline JavaScript syntax checked. Existing Admiralty table values preserved except the requested TNA correction; five rows added. Unrelated indexed records preserved. Search HTML changed only to reference the refreshed index.

Files
admiralty-publications.html
documents-on-british-foreign-policy.html
index.html
naval-arms-control.html
search-index-comprehensive-v105.js
search.html
whats-new.html
