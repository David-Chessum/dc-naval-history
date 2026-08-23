DC Naval History - Step 5 Batch Update
Date: 23 August 2026

This batch implements Step 5 of the site improvement plan.

Changes:
- Adds Search to the site-wide header navigation immediately before Contact.
- Adds search.html.
- Adds search-index.js.
- Search covers:
  * page titles
  * page text
  * research table contents
- Search section filters use checkboxes, all selected by default.
- Matching table records are grouped under their parent page.

Deployment:
Replace the corresponding HTML files on the site with the files in this batch.
Upload the new search.html and search-index.js files.

Important:
search.html requires search-index.js to be present in the same site directory.
