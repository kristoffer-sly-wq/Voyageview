# Voyage View Fast Canvas V3

This version keeps the dashboard as one simple `index.html` file, but adds:

- Editable TV summary text
- Summary is saved locally in the browser
- Summary is included in downloaded `voyage-data.json`
- 1-minute video with proper camera movement:
  - 0–5 sec: world overview
  - 5–16 sec: zoom to route
  - 16–27 sec: zoom to current position
  - 27–38 sec: zoom back to full route
  - 38–60 sec: hold final readable display
- ETA / position / distance panels stay visible from second 0
- Route draws during the first 10 seconds

## Upload to GitHub

Delete the old files and upload:

- `index.html`
- `README.md` optional

Then hard refresh the site with Ctrl + F5.

## Note

Map tiles are loaded online. If the vessel network blocks tile access, the dashboard still works but the map background may be plain.
