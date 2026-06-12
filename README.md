# Voyage View Fast Canvas V2

This is a simpler and faster version.

## What changed

- Single-file app: only `index.html` is required.
- No JSON dependency.
- No MapLibre dependency.
- Upload RTZ directly in the page.
- Real online map tiles are drawn on a canvas.
- All position / ETA / distance information is visible from second 0.
- The route draws during the first 12 seconds, then the video holds the final display.
- 1-minute video export records the full dashboard canvas, not only the map.

## Upload to GitHub

Delete the old files and upload only:

- `index.html`
- `README.md` optional

Then GitHub Pages will serve the new app.

## Note

The map tiles require internet access. If map tiles are blocked by the vessel network, the dashboard still renders but the map background may look plain.
