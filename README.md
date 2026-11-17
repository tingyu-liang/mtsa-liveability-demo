# MTSA Liveability Explorer
An interactive MUCP demonstration built with React, TypeScript, Vite, and Leaflet.

## Development
`npm install` then `npm run dev`. Run `npm run build` for type checking and the production bundle.

## Content
Edit `src/data.ts` to replace sample sites, categories, and written information. All current descriptions are illustrative, not verified study findings. Coordinates are approximate. The generated polygons are illustrative study footprints, not official MTSA boundaries. Replace them with validated GeoJSON before presenting geographic claims.

The map uses OpenStreetMap raster tiles and attribution. External basemap access is required; the list and study panels work independently of tile loading. Fonts load from Google Fonts with local fallbacks. No account, backend, or database is required.

## Interactions
Choose a community, toggle any combination of challenge categories (OR matching), click a map marker or list item, and switch between challenge/proposal tabs. Filtering a selected site out closes its panel. Reset restores all sites. Escape closes the site panel or About dialog.
