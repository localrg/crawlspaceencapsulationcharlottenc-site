# Catawba Crawlspace Co. Authority Cluster Report

Date: 2026-06-18
Site: https://crawlspaceencapsulationcharlottenc.com/
Brand: Catawba Crawlspace Co.
Market: Charlotte, NC

## Outcome

The Charlotte crawlspace site is complete for the topical authority pass, has been corrected to present the authority content as readable articles instead of directory-style resource cards, and now uses clean extensionless public URLs.

The site now has a connected crawlspace knowledge base around four authority hubs:

- Core services: inspection, vapor barrier installation, moisture control, drainage and waterproofing, dehumidifiers, insulation.
- Problems: wet crawl space, mold smell, standing water, sagging floors, high humidity, wood rot.
- Decisions: cost in Charlotte, encapsulation vs vapor barrier, DIY vs professional work, whether encapsulation is worth it.
- Local proof: Charlotte clay soil and humidity, Gaston and Mecklenburg service area, local project planning example.

## On-Page.ai Starting Point

Homepage scan:

- URL: https://crawlspaceencapsulationcharlottenc.com/
- Keyword: crawlspace encapsulation charlotte nc
- Score: 87/100
- Grade: Strong
- Job display ID: job_759bd3e0...e191
- Powered by: On-Page.ai

Main read: the homepage was already a strong foundation, so the right move was not a full rewrite. The useful gap was topical authority: more connected pages proving service, problem, material, condition, local, and outcome entities.

## Work Completed

- Added 23 new authority pages across services, problems, guides, and local proof.
- Added the homepage "Charlotte Crawl Space Authority Cluster" section.
- Added internal authority links to the existing city pages.
- Updated the sitemap to 47 public indexable URLs.
- Kept Web3Forms lead routing and thank-you flow in place.
- Fixed mobile navigation so the header links and phone CTA remain visible on small screens.
- Bumped the stylesheet cache key to `styles.css?v=20260618-authority2`.

## Article Presentation Correction

- Added a new article library at `/blog/`.
- Changed the top navigation to `Home`, `Services`, `Articles`, and `Areas`.
- Reworked `services/`, `problems/`, `guides/`, and `local/` into article-category archives.
- Converted the 19 supporting authority pages into article-style pages with article metadata, reading labels, and "Read next" language.
- Replaced the visible "pages in this section" / "Explore the cluster" pattern with article cards.
- Updated the homepage authority section to point users into the article library.
- Updated the sitemap to 48 public indexable URLs after adding `/blog/`.
- Bumped the stylesheet cache key to `styles.css?v=20260618-blogposts`.

## Extensionless URL and Authority Silo Correction

- Removed `.html` from public canonical URLs, Open Graph URLs, sitemap URLs, footer links, article links, city links, and form redirect targets.
- Added `.htaccess` redirects so old `.html` URLs 301 to the clean extensionless versions.
- Kept the Google verification `.html` file working as an explicit exception.
- Added homepage authority uplink sections to 44 supporting pages and archives.
- Used the homepage anchor text `Crawlspace Encapsulation in Charlotte NC` from supporting service, problem, guide, local, blog, and city pages.
- Kept supporting pages linked into the article/service structure while rolling the primary crawlspace authority back toward the homepage.
- Bumped the stylesheet cache key to `styles.css?v=20260618-extensionless`.

## Deployment Proof

- GitHub commit: `823c2658f6d39ec5a954a79e7f47b08bed61ed28`
- Branch: `main`
- Hostinger deploy evidence: `site-factory/run-logs/charlotte-extensionless-silo-retry-hostinger-deploy-20260618-150522.json`
- Deploy archive: `site-factory/deploy-archives/crawlspaceencapsulationcharlottenc-site-public_20260618_150522.zip`
- Previous failed upload attempt: `site-factory/run-logs/charlotte-extensionless-silo-hostinger-deploy-20260618-150340.json`
- Upload failure note: the first Hostinger TUS PATCH returned 404, so the deploy helper was hardened to PATCH Hostinger's returned upload `Location` and retry fresh upload credentials.
- Live homepage: 200 HTTPS
- Live robots.txt: 200 HTTPS
- Live sitemap.xml: 200 HTTPS
- Live sitemap URL count: 48
- Live article library: https://crawlspaceencapsulationcharlottenc.com/blog/
- Live local article archive: https://crawlspaceencapsulationcharlottenc.com/local/
- Verified live authority page: https://crawlspaceencapsulationcharlottenc.com/services/crawl-space-moisture-control
- Verified clean local article: https://crawlspaceencapsulationcharlottenc.com/local/charlotte-clay-soil-crawlspace-moisture
- Verified old `.html` redirects: representative article, service, city, and privacy-policy URLs 301 to extensionless URLs.
- Verified Google exception: https://crawlspaceencapsulationcharlottenc.com/google0601bb32c31c28cd.html remains 200.

## Validation

- Static validation: passed
- Validation file: `reports/static-validation.json`
- Checks: 25 total, 0 failed
- Local HTML files: 50
- Sitemap URLs: 48
- Sitemap `.html` URL count: 0
- Internal link missing count: 0
- Internal `.html` reference count: 0
- Authority uplink missing count: 0
- Homepage authority uplink pages: 44
- Browser QA: article archive, blog index, and representative article pages rendered without horizontal overflow, with visible article metadata, article cards, forms present, and mobile navigation visible.

## Notes

- Clarity was skipped per Bryan's instruction.
- Citation and social profile work is separate from this topical authority pass unless assigned next.
