# AGENTS

## Repository overview

This repository is a static website for `caboose-www` deployed on Cloudflare via github.

### Source layout
- Root-level HTML pages: `index.html`, `about.html`, `awards.html`, `brewery.html`, `coffee.html`, `fairfax.html`, `food.html`, `happenings.html`, `privacy-policy.html`, `private-events.html`, `vienna.html`
- Styles: `css/styles.css`
- Scripts: `js/main.js`
- Images and media: `img/`

## Deployment

- Deployed to Cloudflare using the Cloudflare Workers/Wrangler site deployment configuration in `wrangler.jsonc`.
- `assets.directory` is set to `.` so the site is published from the repository root.
- The project has no build step or package manager files in this repo.

## Preferred MCP Servers / Agents
- Github CoPilot
- Claude Code
- Github MCP Server


## Notes for contributors

- Edit HTML files directly in the repo root for page content changes.
- It is important to remember that any changes to headers or footers need to be reflect on each page.
- Update `css/styles.css` for styling changes.
- Update `js/main.js` for client-side behavior.
- Add new static assets under `img/` and reference them from HTML or CSS.
- Deployment changes are managed via Cloudflare configuration in `wrangler.jsonc`.
- For automated workflows, prefer the GitHub MCP server as an integral part of agent-driven PR and deployment planning.

## Modification Requests / Issues List

- Issues are tracked at https://docs.google.com/document/d/1W2weQMBchHYtjDi9AVSQWJu-Zv_F85z_5EyKbszVWQ4/edit?tab=t.0
- Items that are easily dealt with should be marked as resolved in the google document above.
- If follow-up or questions about the changes required are needed, a comment within the google document should be used to track the information being requested.
