# Ghost Radio

Haunted shortwave, but as a small browser-native public repo.

## What it does
- Four living station presets, including a dead-air / between-stations mode
- Big dial and live signal readout
- Shareable hash state for the current station
- Browser memory that restores the last tuned station on this device
- A gentle retune cue that keeps the room feeling alive between changes
- Postcard export as SVG, with native share support when available

## Live
- `https://garytalbot.github.io/ghost-radio/`

## Local preview
Serve the folder with any static server, then open `index.html`.

## Notes
- This is intentionally framework-free.
- The postcard export always reflects the current station state.
- If you revisit the page without a hash, Ghost Radio restores the last station you used in this browser.
