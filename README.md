# Erroris starter

Open `dist/index.html` in a browser, or run `python -m http.server 4173 --directory dist` from this folder and visit http://localhost:4173.

Dependency-free static website with 130 catalogue entries: 10 guided troubleshooting records and 120 reviewed source references. Covers 21 manufacturers plus Windows and OBD-II diagnostic contexts. Includes brand filters, product/model matching, coverage reporting, repair summaries and local saved devices. Reference entries deliberately have no DIY score or reviewed repair procedure.

Coverage is deliberately explicit. No AI inference, OCR, live search API, automatic video ranking, or service booking is implemented. Exact model matching applies only to the finite models listed in a record, not arbitrary models or series suffixes. Unknown codes return a no-match state with external search links. Device records stay in browser localStorage; external searches send the chosen terms to Google or YouTube.

Published via GitHub Pages: https://thefamousjc.github.io/erroris/ — repository https://github.com/TheFamousJC/erroris. The repository root contains the contents of dist.

Collection workflow: see scripts/COLLECTION.md. Run `node scripts/build-catalogue.cjs`, `node scripts/test-catalogue.cjs` and `node scripts/test-collector.cjs`. The collector produces review candidates only. This import used web-assisted manufacturer-page extraction; the local HTTP crawl was blocked by DNS and produced no new candidates. Never put provider secrets in browser code.
