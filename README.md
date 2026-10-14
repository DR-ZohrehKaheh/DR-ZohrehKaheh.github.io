# Dr Zohreh Kaheh — research website

Personal research website: **https://dr-zohrehkaheh.github.io/**

Static HTML and CSS, hosted with GitHub Pages. No package installation, build service, analytics or paid domain is required.

## Content

- `index.html`: profile, research themes, five software projects, seven selected publications, background, teaching and contact.
- `styles.css`: responsive layout, keyboard focus, reduced-motion and print styles.
- `sources.html`: content sources and attribution notes.
- `sitemap.xml`, `robots.txt`: crawler discovery.
- `favicon.svg`, `404.html`, `.nojekyll`: icon, error page and static hosting.

## GitHub Pages

In **Settings → Pages**, choose **Deploy from a branch**, branch **main**, folder **/(root)**. The canonical site URL is `https://dr-zohrehkaheh.github.io/`.

## Editing

Edit content in `index.html`. Preserve collaborator credits, citation author order, DOI types and project limitations. Avoid asserting a current institutional appointment. After substantive changes, update the review date in `sources.html`, `dateModified` in the structured data, and `lastmod` in `sitemap.xml`. Google’s `ProfilePage.dateModified` expects a full ISO 8601 date-time including the actual time and timezone (for example, `2026-10-14T13:00:00+03:00`), not a date-only value. Sitemap `lastmod` may remain a date. Use the real modification time, not a future date or the time of an unrelated redeployment.

Content sources are linked in `sources.html`. The distributed-procurement article shows its 2022 online publication date alongside its final 2024 journal issue citation. The selected publications include four journal articles, one conference paper and two book chapters, with explicit type labels and DOI links. Discontinued Brunel staff-profile links have been removed; historical teaching and funding provenance is explained in `sources.html`.

## Search discovery

The site includes a descriptive title and description, canonical URL, sitemap, robots file, crawlable HTML, and ProfilePage/Person structured data. Link this website from public professional profiles. The URL-prefix property `https://dr-zohrehkaheh.github.io/` was verified in Google Search Console on 13 October 2026 using `google0e35955c171c9184.html`. Keep this verification file in place to retain ownership verification. On 13 October 2026, URL Inspection confirmed the homepage with `URL is on Google` and `Page is indexed`; Googlebot fetched it successfully and selected the declared canonical URL. An indexing request for `sources.html` was also accepted and added to Google's crawl queue. The sitemap report still showed `Couldn't fetch`, and the homepage's sitemap discovery field showed `Temporary processing error`. The published sitemap, robots file and both HTML pages returned HTTP 200 without redirects; the sitemap parsed as valid XML with `application/xml`, and Google's live sitemap test reported a successful fetch with crawling allowed. Manual actions and Security issues both reported no issues. Sitemap processing and the sources page still need a later check. Indexing of the homepage does not guarantee rankings or indexing of every page.

Official guidance:

- https://docs.github.com/en/pages/quickstart
- https://developers.google.com/search/docs/fundamentals/seo-starter-guide

## Rights

© 2026 Zohreh Kaheh. No general reuse licence is granted for this website. Linked research projects and publications have separate rights statements. Public visibility and citation do not confer reuse rights.


## Security and privacy

The public pages use a restrictive meta Content Security Policy: no executable scripts, third-party resource loading, frames, plugins or form submissions. Same-origin CSS and images remain allowed. `application/ld+json` is an inert data block used for search metadata, not executable JavaScript. A `no-referrer` policy avoids sending the referring page to linked websites.

HTTPS redirects and the hosting platform's HSTS header were observed on 14 October 2026. These headers are controlled by GitHub Pages. Meta CSP does not support `frame-ancestors`; do not add a pretend frame-protection meta tag or claim that this site prevents being embedded. Custom server response headers require a host or proxy that supports them. No hosting migration is required for this static portfolio.

Keep the Google verification file unchanged. Do not put credentials, private documents or personal contact details in this public repository. Account two-factor authentication, app permissions and repository access controls are separate from these site-source protections and were not changed in this audit.

The former COGITO project-site PDF link returned an unexpected cross-domain redirect during the October 2026 review. It has been replaced with the European Commission's CORDIS results record and official document-download link.

## Checks before publishing

- Parse JSON-LD and sitemap XML; check the `ProfilePage` timestamp includes a timezone.
- Check all local files and fragment links, publication DOI links and contributor attribution links.
- Check keyboard navigation, text contrast and layouts at narrow and wide widths. The CSS includes larger touch targets and a single-column publication layout below 380px.
- Preserve the two canonical sitemap URLs and the ownership-verification file.
- After deployment, run Google's Rich Results Test against the live URL and use **Validate fix** for the existing Search Console warning. A successful deployment or a valid local parse is not proof of Google validation or indexing.

`assets/social-card.png` is a local sharing preview, not a profile photograph; it is deliberately not used as `Person.image`.

Implementation references:

- https://developers.google.com/search/docs/appearance/structured-data/profile-page
- https://developer.mozilla.org/en-US/docs/Web/HTTP/Guides/CSP
- https://developer.mozilla.org/en-US/docs/Web/HTTP/Reference/Headers/Referrer-Policy
- https://www.w3.org/WAI/WCAG22/Understanding/contrast-minimum.html
- https://www.w3.org/WAI/WCAG22/Understanding/target-size-minimum.html
