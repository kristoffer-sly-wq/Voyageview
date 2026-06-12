# Voyage View Fast Canvas V6

V6 adds proper close zoom again, but makes it safe for route visibility.

Changes:
- Added editable Video animation settings:
  - Use close zoom during video
  - Close zoom level
  - Close view hold seconds
- Close zoom centers on the active RTZ route segment, not only the ship position.
- Strong local route tangent is drawn through the projected position, so the route remains visible even at close coastal zoom.
- Still keeps ETA / position / distance panels visible from second 0.
- Editable summary text remains.

Recommended settings:
- Offshore crossing: close zoom level 5.5–6.2
- Coastal voyage: close zoom level 6.5–7.8
- Port approach / short route: close zoom level 7.5–8.5

Upload only:
- index.html
- README.md optional

After upload, hard refresh with Ctrl + F5.
