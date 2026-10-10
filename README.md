# Expressions Graphic Design

Static site for Expressions Graphic Design, hosted on Cloudflare Pages.

- `public/index.html` is the whole page (HTML, CSS and JS inline).
- `public/assets/` holds the logos and photos.
- `public/_headers` sets long caching for `assets/`.
- `wrangler.jsonc` tells Cloudflare to serve `public/` as static files.

There is no build step. Cloudflare's Git integration runs `npx wrangler deploy`, and every push to `main` deploys automatically.
