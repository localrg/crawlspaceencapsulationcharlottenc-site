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

## Question-Based Blog URL Correction

- Moved the 19 supporting authority posts to question-style `/blog/` permalinks.
- Changed blog titles and H1s from category/service-style labels to informational questions, such as `Why Does My Crawl Space Smell Musty?`, `How Much Does Crawl Space Encapsulation Cost in Charlotte?`, and `Why Do Charlotte Crawl Spaces Have Moisture Problems?`.
- Removed `services/`, `problems/`, `guides/`, and `local/` article category archives from the sitemap and internal article navigation.
- Added `.htaccess` 301 redirects from every old article URL under `services/`, `problems/`, `guides/`, and `local/` to the matching new `/blog/` URL.
- Redirected the old article-category archive paths to `/blog/`.
- Kept the homepage authority link on each blog post with the anchor `Crawlspace Encapsulation in Charlotte NC`.
- Updated the blog archive to group posts as service questions, problem questions, decision questions, and Charlotte moisture questions.
- Updated the sitemap to 44 public indexable URLs.
- Bumped the stylesheet cache key to `styles.css?v=20260618-blogquestions`.

## Extensionless URL and Authority Silo Correction

- Removed `.html` from public canonical URLs, Open Graph URLs, sitemap URLs, footer links, article links, city links, and form redirect targets.
- Added `.htaccess` redirects so old `.html` URLs 301 to the clean extensionless versions.
- Kept the Google verification `.html` file working as an explicit exception.
- Added homepage authority uplink sections to 44 supporting pages and archives.
- Used the homepage anchor text `Crawlspace Encapsulation in Charlotte NC` from supporting service, problem, guide, local, blog, and city pages.
- Kept supporting pages linked into the article/service structure while rolling the primary crawlspace authority back toward the homepage.
- Bumped the stylesheet cache key to `styles.css?v=20260618-blogquestions`.

## Blog Scaffold Copy Cleanup

- Removed internal SEO/scaffold phrasing from the blog posts and city authority blocks.
- Replaced `This blog post supports the main crawlspace encapsulation page...` with homeowner-facing copy about inspecting the crawl space and deciding whether encapsulation, drainage, vapor barrier work, insulation changes, or humidity control make sense.
- Replaced generic hero-panel copy like `This article explains one part of the crawl space decision...` with a natural `Short answer` panel.
- Replaced repeated placeholder card copy like `This detail helps connect the visible crawl space condition...` with more reader-facing inspection language.
- Fixed a related-card label that was displaying `cities/` as visible text.
- Preserved the homepage authority link on each blog post.

## Two-Column Blog Template Correction

- Rebuilt all 19 individual blog posts into a true article template: hero first, then one article section.
- Changed the post body layout to a 66/33-style split: left column for the article answer, headings, and body copy; right sidebar for the contact form, homepage service link, related articles, phone, and address.
- Removed the post-level authority uplink block, key-takeaway card grid, read-next card grid, and separate bottom contact section from the 19 individual posts.
- Rewrote each post body so the visible content directly answers the question in the H1.
- Preserved internal linking from each post to the homepage with `Crawlspace Encapsulation in Charlotte NC`.
- Bumped the post stylesheet cache key to `styles.css?v=20260618-blogtemplate`.

## Deployment Proof

- GitHub commit: `4e82ec012616dfc3d7a96a450ed0565046e94a51`
- Branch: `main`
- Hostinger deploy evidence: `site-factory/run-logs/charlotte-blog-template-hostinger-deploy-20260618-162147.json`
- Deploy archive: `site-factory/deploy-archives/crawlspaceencapsulationcharlottenc-site-public_20260618_162147.zip`
- Previous failed upload attempt: `site-factory/run-logs/charlotte-extensionless-silo-hostinger-deploy-20260618-150340.json`
- Upload failure note: the first Hostinger TUS PATCH returned 404, so the deploy helper was hardened to PATCH Hostinger's returned upload `Location` and retry fresh upload credentials.
- Live homepage: 200 HTTPS
- Live robots.txt: 200 HTTPS
- Live sitemap.xml: 200 HTTPS
- Live sitemap URL count: 44
- Live article library: https://crawlspaceencapsulationcharlottenc.com/blog/
- Old local article archive redirects to: https://crawlspaceencapsulationcharlottenc.com/blog/
- Verified live authority page: https://crawlspaceencapsulationcharlottenc.com/blog/how-do-you-control-moisture-in-a-crawl-space
- Verified clean local article: https://crawlspaceencapsulationcharlottenc.com/blog/why-do-charlotte-crawl-spaces-have-moisture-problems
- Verified question post examples: `/blog/why-does-my-crawl-space-smell-musty`, `/blog/how-much-does-crawl-space-encapsulation-cost-in-charlotte`, and `/blog/why-do-charlotte-crawl-spaces-have-moisture-problems` return 200.
- Verified old article redirects: representative `local/`, `services/`, `problems/`, and `guides/` URLs 301 to matching `/blog/` question URLs.
- Verified old `.html` redirects: representative article, service, city, and privacy-policy URLs redirect to clean URLs.
- Verified scaffold copy cleanup: representative live blog and city pages no longer include the internal-support/scaffold phrases.
- Verified two-column blog template: representative live posts contain `blog-layout`, `blog-main`, `blog-sidebar`, sidebar form, related links, homepage link, and no old scaffold/card-section phrases.
- Verified Google exception: https://crawlspaceencapsulationcharlottenc.com/google0601bb32c31c28cd.html remains 200.

## Validation

- Static validation: passed
- Validation file: `reports/static-validation.json`
- Checks: 25 total, 0 failed
- Local HTML files: 46
- Blog post files: 19
- Sitemap URLs: 44
- Sitemap `.html` URL count: 0
- Internal link missing count: 0
- Internal `.html` reference count: 0
- Internal old article-folder reference count: 0
- Authority uplink missing count: 0
- Homepage authority uplink missing count on blog posts: 0
- Two-column blog template missing count: 0
- Blog post old scaffold phrase count: 0
- Browser QA: Live HTTP checks passed for the blog index and representative question posts. Playwright is not installed in this repo, so screenshot-based browser QA was not available.

## Notes

- Clarity was skipped per Bryan's instruction.
- Citation and social profile work is separate from this topical authority pass unless assigned next.
