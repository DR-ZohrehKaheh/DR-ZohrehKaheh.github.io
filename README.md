# Dr Zohreh Kaheh — research website

Personal research portfolio: **https://dr-zohrehkaheh.github.io/**

The website presents research themes, six software projects, seven selected publications, professional background and teaching experience. It uses static HTML and CSS, hosted on GitHub Pages.

## Site files

- `index.html`: the main portfolio and profile metadata.
- `sources.html`: research references, contributor credits and privacy information.
- `styles.css`: responsive layout, keyboard focus, reduced-motion and print styles.
- `sitemap.xml` and `robots.txt`: search discovery.
- `assets/social-card.png` and `favicon.svg`: sharing preview and site icon.
- `404.html`: custom error page.
- `google0e35955c171c9184.html`: Google ownership verification; preserve this file.

## Publishing and maintenance

GitHub Pages deploys from the `main` branch at the repository root. Preserve the site URL, contributor credits, publication details and DOI identifiers when editing. Keep descriptions of past research and teaching distinct from current appointments.

After substantive content changes, update relevant sitemap modification dates and the profile’s `dateModified` value using an actual ISO 8601 timestamp with timezone. Check local links, metadata and mobile and desktop layouts, then confirm successful deployment.

The Google verification file must remain in place. Search indexing and result presentation are managed separately through Search Console.

## Privacy and browser policies

The site has no analytics, advertising, tracking pixels or contact-form backend. Styles and images are served locally. A restrictive meta Content Security Policy limits resource loading, and the referrer policy is `no-referrer`.

GitHub Pages manages HTTPS and HTTP response headers. The meta policy does not provide `frame-ancestors` protection. Account security and repository permissions are separate from website content and browser policies.

## Rights

© 2026 Zohreh Kaheh. No general reuse licence is granted for this website. Linked research projects, publications and third-party materials retain their own rights and attribution requirements.

## Documentation

- [GitHub Pages](https://docs.github.com/en/pages/quickstart)
- [Google ProfilePage structured data](https://developers.google.com/search/docs/appearance/structured-data/profile-page)
- [Content Security Policy](https://developer.mozilla.org/en-US/docs/Web/HTTP/Guides/CSP)
