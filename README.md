# Brandon Schmidt — Projects Portfolio

A single-page portfolio covering product/UI design, AI automation, security, and home-lab work, styled as a technical drawing set (blueprint concept, tied to an AutoCAD drafting background).

Live site: https://sansctf.github.io/brandon-portfolio/

## Run locally

```
bun install   # or: npm install
bun run dev   # or: npm run dev
```

Opens the site at `http://localhost:5173`.

## Build

```
bun run build   # or: npm run build
```

Outputs static files to `dist/`.

## Deploy

Pushing to `main` triggers `.github/workflows/deploy.yml`, which publishes the `site/` folder directly to GitHub Pages — no build step required, since the page is self-contained static HTML/CSS with inlined images.
