# Expressions Graphic Design

Static site for Expressions Graphic Design, hosted on Cloudflare Pages.

- `index.html` is the whole page (HTML, CSS and JS inline).
- `assets/` holds the logos and photos.
- `_headers` sets long caching for `assets/`.

There is no build step. In Cloudflare Pages, leave the build command empty and set the output directory to `/`. Every push to `main` deploys automatically.
