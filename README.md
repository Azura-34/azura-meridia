# AZURA × MERIDIA

Premium, responsive Turkish corporate landing page for the AZURA and MERIDIA technology brands. Built as plain static HTML, CSS, and JavaScript so it can be served directly as Cloudflare Workers Static Assets from the repository root.

## Run locally

1. Install Node.js.
2. From this folder, run `npm install`.
3. Run `npm run dev` and open the local URL Wrangler prints.

## Cloudflare

The included `wrangler.jsonc` serves the repository root as Worker static assets. `.assetsignore` keeps project metadata out of the public asset collection. To deploy from this folder, authenticate Wrangler with the Cloudflare account connected to the intended project, then run `npm run deploy`.

## Before launch

- The contact CTA currently opens `hello@azura-meridia.com`. Replace it in `index.html` with the verified company inbox before publishing.
- Google Fonts are loaded from Google Fonts; local serif and sans-serif fallbacks are included.
- The hero uses the supplied image unchanged at `azura-meridia-hero-original.png` so the two characters' faces and physical features stay exactly as provided. A dark overlay masks the embedded screenshot copy behind the live page text and navigation.

## Project structure

```text
azura-meridia-hero-original.png
favicon.svg
index.html
main.js
styles.css
package.json
wrangler.jsonc
.assetsignore
```
