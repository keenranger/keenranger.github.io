# keenranger.github.io

Personal site for [Hankyeol Kyung](https://github.com/keenranger), an AI/agent
engineer working on practical systems for memory, runtime, deployment, and
human-AI collaboration.

The site is a deliberately thin public layer over a private, markdown-first
knowledge system. It publishes selected projects, writing, and working beliefs
without mirroring private context or internal work details.

## What is here

- **Home** — current focus and the main project threads
- **Projects** — SleepHub, Knowledge OS, agent infrastructure, and public tools
- **Writing** — notes from the workbench
- **Direction** — beliefs about durable agents, explicit memory, and runtime
- **About / Links** — background and public contact surfaces

Built with [Astro](https://astro.build/) and deployed with GitHub Pages.

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
  pages/                # routes: /, /about, /projects, /writing, /direction, /links
  styles/global.css     # minimal global styles
public/
  favicon.svg
```

## Deploy

Push to `main` triggers GitHub Actions build + deploy to GitHub Pages.
