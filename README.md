# keenranger.github.io

Personal site for Hankyeol Kyung. Astro + GitHub Pages.

## Development

```bash
pnpm install
pnpm dev        # http://127.0.0.1:4321
pnpm build      # static output in dist/
pnpm preview    # preview built site
```

## Structure

```
src/
  layouts/Base.astro    # shared layout + nav
  pages/                # routes: /, /about, /projects, /writing, /links
  styles/global.css     # minimal global styles
public/
  favicon.svg
```

## Deploy

Push to `main` triggers GitHub Actions build + deploy to GitHub Pages.
