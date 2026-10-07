# BiVa Travel — World Map Data

Free, click-to-explore map data for **bivatravel.blogspot.com**.
Every country of the world, with its provinces / states / districts as separate clickable shapes.

**242 countries · 4,123 clickable regions · public domain · no API key · no server**

## Files
| File | What it is |
|---|---|
| `index.json` | every country: slug, name, continent, region count, file name (~25 KB) |
| `world-lite.json` | the world map used on the site (110m shapes + dots for tiny countries) — 96 KB |
| `world.json` | higher-detail world map (50m), 819 KB — optional upgrade |
| `maps/<slug>.json` | one country's map: `viewBox` + array of regions with SVG path data |

Region files average **38 KB** (gzipped ~10 KB) and are loaded **only when a visitor clicks that country**,
so the site stays fast even though the whole world is covered.

## Used by
`https://bivatravel.blogspot.com/p/travel-map.html` (BiVa Travel's "My Travel Map" tool).

## Data sources & licence
- **Natural Earth** (1:110m / 1:50m Admin-0, 1:10m Admin-1) — **public domain**, no restrictions, commercial use allowed.
- **geoBoundaries** (gbOpen) — used for Afghanistan's official 34 provinces — **public domain**.
Everything here is derived map geometry; no personal data, no tracking data.

## Attribution shown on the site
> Map data: Natural Earth & geoBoundaries (public domain)
