# AGENTS

## Repository overview

This repository is a static website for `caboose-www` deployed on Cloudflare.

### Source layout
- Root-level HTML pages: `index.html`, `about.html`, `awards.html`, `brewery.html`, `coffee.html`, `fairfax.html`, `food.html`, `happenings.html`, `privacy-policy.html`, `private-events.html`, `vienna.html`
- Styles: `css/styles.css`
- Scripts: `js/main.js`
- Images and media: `img/`

## Deployment

- Deployed to Cloudflare using the Cloudflare Workers/Wrangler site deployment configuration in `wrangler.jsonc`.
- `assets.directory` is set to `.` so the site is published from the repository root.
- The project has no build step or package manager files in this repo.

## Notes for contributors

- Edit HTML files directly in the repo root for page content changes.
- Update `css/styles.css` for styling changes.
- Update `js/main.js` for client-side behavior.
- Add new static assets under `img/` and reference them from HTML or CSS.
- Deployment changes are managed via Cloudflare configuration in `wrangler.jsonc`.
- For automated workflows, prefer the GitHub MCP server as an integral part of agent-driven PR and deployment planning.
