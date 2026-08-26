# winkler.dev

Static single-page site for https://winkler.dev/. No build step: `site/` is deployed as-is to the `gh-pages` branch on every push to `master` (see `.github/workflows/deploy.yml`), then the Cloudflare cache is purged.

Preview locally:

```sh
python3 -m http.server -d site 8000
```

Fonts (Archivo Black, Source Code Pro 500 — latin subsets) are self-hosted from `site/fonts/`.
