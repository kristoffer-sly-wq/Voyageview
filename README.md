# Voyage View Fast Canvas V7

Fixes from V6:
- Fixed disappearing route line.
- The old code broke the route when screen distance between waypoints was large.
- That was meant to prevent dateline/world-wrap drawing, but it incorrectly broke long ocean legs.
- V7 now draws the RTZ route continuously.
- Remaining route line is stronger.
- Full route centerline is drawn after sailed/remaining so it remains visible at close zoom.
- Close zoom settings and editable summary remain.

Upload only:
- index.html
- README.md optional

After upload:
1. Wait for GitHub Pages deployment.
2. Open the site.
3. Press Ctrl + F5.
