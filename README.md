# Normand Maximus MapLibre Voyage Dashboard

This version replaces the ugly drawn map with a real interactive web map using MapLibre GL JS and online basemap tiles.

## Features

- Real world map with pan / zoom
- Dark, light, and satellite basemap buttons
- Upload any RTZ route in the browser
- Route draws automatically from RTZ waypoints
- Current position marker
- Sailed estimate and remaining estimate
- Daily editor for position, COG, SOG, HDG, Avg SOG
- Manual overrides for ETA and distances
- Download PNG
- Download 1-minute map video

## Important

The map tiles are loaded from the internet. If the vessel network blocks map tile/CDN access, the map will not display until those domains are reachable.

The video download is WebM because the site is static GitHub Pages. Convert to MP4 with VLC, HandBrake, ffmpeg, or PowerPoint if your TV system requires MP4.

## Upload to GitHub

Replace the old files in the repo with these:

- index.html
- style.css
- app.js
- data/
- route-data.json
- voyage-data.json
- samples/

After upload:
1. Go to GitHub Actions.
2. Wait for the Pages deployment to finish.
3. Open the site.
4. Hard refresh with Ctrl + F5.

## Operational note

Distances and ETA are estimates for display only. Use manual overrides to match the official bridge figures.
