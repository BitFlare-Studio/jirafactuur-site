# jirafactuur-site

The public marketing site for Jira Factuur, served via GitHub Pages. A single-page app: `index.html` holds
Overview, Documentation, Privacy & security and Support as four panels, switched client-side by a tiny script
keyed off `location.hash` (`#overview`, `#docs`, `#privacy`, `#support`) — no separate pages, no reloads.
`images/` holds the screenshots the Documentation panel uses.

This repo is separate from [`Jirafactuur`](https://github.com/BitFlare-Studio/Jirafactuur) (the Forge app itself,
which is private) purely so the site can be public without exposing the app's source. Source copy for the
content originates from that repo's `branding_pages/` folder — when the app's feature set changes, update there
first, then mirror the changes here.

Custom domain (`jirafactuur.nl`) is configured separately in the repo's GitHub Pages settings.
