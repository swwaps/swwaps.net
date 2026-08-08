# swwaps.net

Public website of **Southwestern Washington Paddling Sports (SWWAPS)**, a nonprofit and home of the Calapya dragon boat team.

Plain static HTML/CSS — no build step. Hosted on GitHub Pages.

## Pages

Clean URLs via directory-style pages (each page is `<name>/index.html`):

- `/` — Home (`index.html`)
- `/team/` — The Team (Calapya)
- `/events/` — Events & 2026 race calendar
- `/faq/` — FAQ
- `/board/` — Board of directors
- `/support/` — Sponsors & support

Shared styles live in `css/site.css` (design tokens from the 2026 redesign handoff). Brand SVGs are in `assets/`.

## Photos

All photos, headshots, and sponsor logos are currently placeholder blocks (`<div class="photo-slot">…</div>`). When the club supplies images, replace each placeholder with a plain `<img>` (keep the wrapper's aspect-ratio and the slot's border-radius: 24px hero photos, 20px fun-run photo, circular 132px headshots, contain-fit sponsor logos).

## Local preview

Open any page directly in a browser, or:

```
python3 -m http.server 8080
```
