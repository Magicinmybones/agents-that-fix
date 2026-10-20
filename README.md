# Agents That Fix

Static site built from the supplied HTML prototype. The deployable files are in `public/`; no build step or runtime dependencies are needed. Fonts and imagery are in `public/assets/`.

Deploy to Cloudflare Pages:

```sh
npx wrangler pages deploy public --project-name agents-that-fix --branch main
```
