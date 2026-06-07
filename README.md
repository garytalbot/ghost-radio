# Ghost Radio

Haunted shortwave, but as a small browser-native public repo.

## What it does
- Four preset states: Attic, Hallway, Moon, and Dead air
- Broadcast log / station diary for recent tuning notes
- Big dial and live signal readout
- Shareable hash state for the current station
- Browser memory that restores the last tuned station on this device
- A gentle retune cue that keeps the room feeling alive between changes
- Listen closer mode that pins the signal and lets the current broadcast breathe into a second whisper
- Side chamber: `frequency-veil.html` for a cursor-seeded frequency network toy
- Postcard export as SVG, with live lock state and diary note capture when available
## Live
- `https://garytalbot.github.io/ghost-radio/`

## Local preview
Serve the folder with any static server, then open `index.html`.

## Notes
- This is intentionally framework-free.
- The postcard export always reflects the current station state.
- If you pin the signal before exporting, the postcard includes the live lock state and latest diary note.
- If you revisit the page without a hash, Ghost Radio restores the last station you used in this browser.
