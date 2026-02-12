# steverhall.github.io

Personal site + blog for Steve Hall, built with [Astro](https://astro.build) and deployed to GitHub Pages.

## What’s inside

- 🎯 **Pages:** Home, About, Blog index, and MD/MDX-powered posts stored in `src/content/blog/`
- 💬 **Comments:** [Utterances](https://utteranc.es/) embeds on every post, mapping conversations to GitHub issues
- 📰 **Feeds:** RSS + sitemap configured via Astro integrations
- 🧱 **Design system:** Lightweight typographic styles, hero layout, and cards purpose-built for a calm reading experience

## Development

```bash
npm install
npm run dev      # start local server on http://localhost:4321
npm run build    # output static assets to ./dist
npm run preview  # preview the production build locally
```

## Deployment

This repository is meant to live at `steverhall/steverhall.github.io`, which unlocks the built-in GitHub Pages hosting at <https://steverhall.github.io>. Use the included GitHub Actions workflow (added separately) to build on `main` and publish to `gh-pages`, or serve the `dist/` folder from any static host.

## Comments & issues

Questions, typos, or bug reports? Open an issue or reply directly via Utterances on the relevant post—the comments are synced with this repository.
