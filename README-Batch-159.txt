Batch 159 - 28 November 2026
Baseline: successfully deployed Batch 158.

DEPLOYMENT
1. Back up matching deployed files and pull the latest origin changes.
2. Extract the ZIP separately. Copy all HTML, JavaScript, XML and robots.txt files to the website root, replacing matching filenames. Retain all other files/assets, including naval-header-image-b.png. README and SHA256SUMS are reference files and need not be uploaded.
3. Commit Batch 159, push origin and wait for GitHub Pages deployment to succeed.
4. Hard-refresh. Check Sitemap footer links, expand/collapse controls and hierarchy on desktop/mobile, Home's five updates, Recent Updates announcement, Dresden feature image/website and search.
5. Optionally submit https://dc-naval-history.com/sitemap.xml in Google Search Console after deployment. No Search Console account changes were made.

CHANGES
- Published a visitor sitemap in the standard site style, with collapsible section/country groups and Expand all / Collapse all controls.
- Sitemap hierarchy excludes What's New links and the Home What's New section, prioritises other Home links, orders pages by first link appearance on the parent, and uses breadcrumbs only for Naval Museum Reports.
- Added Sitemap footer links on Home, Search, What's New, the sitemap and the updated Dresden page.
- Added a Website Sitemap announcement dated 28 November 2026 to Recent Updates; added the corresponding Home item and removed the previous fifth item (CID Home Defence Memoranda A Series).
- Added sitemap.xml with canonical destinations, excluding redirects, and robots.txt referencing it. No last-modified dates invented.
- Restyled Militar Historisches Museum, Dresden to the supplied Yasakuni template; first photograph is the feature image with the requested Libelle class caption, official museum website in the top box, all four photos and report text retained.
- Refreshed comprehensive search index to v129, preserving the search interface and duplicate-result handling.

MAINTENANCE
Regenerate sitemaps each deployment using the agreed exclusions/order. Extend footer links to other pages when next edited. Review CSVs, raw crawl files and technical caveats are not published in this package. Robots.txt was absent (HTTP 404), so an allow-all file with Sitemap directive is supplied.

VALIDATION
Visitor sitemap includes all 336 existing non-redirect pages plus itself. XML includes canonical destinations and sitemap.html, no redirects. Home retains five updates; Dresden retains four photos. Embedded JavaScript syntax and ZIP integrity checked; packaged bytes verified. No automatic deployment.

FILES
germany-militar-historisches-museum-dresden.html
index.html
robots.txt
search-index-comprehensive-v129.js
search.html
sitemap.html
sitemap.xml
whats-new.html
