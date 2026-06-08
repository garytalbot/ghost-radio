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
- Side chambers: `frequency-veil.html` (`Frequency Vein`), `signal-basin.html` for an echo-seeded drift field where clicks birth noise-orbit trails, `static-loom.html` for phase-woven static threads that react to your pointer, `drift-oracle.html` for pointer-summoned drift threads with seed sharing, `resonant-spiral.html` for a haunted pointer-driven particle spiral that rewrites its own threads from a seed, `phase-choir.html` for seeded phase-trajectory lines that pull toward the pointer and leave ephemeral ghosts, `echo-weft.html` for a deterministic echo-weave thread field, `hush-lattice.html` for seeded magnetic threads that pulse outward from your clicks, `void-chorus.html` for a glyph storm that drifts toward your cursor, `spectral-threads.html` for a deterministic spectral thread field with seed sharing and pointer pull, `phase-threshold.html` for a phase-biased pointer field where chaos/drift/frequency controls reshape particle threads, `echo-well.html` for a seedable node-field that turns your clicks into drifting signal ghosts, `void-loom.html` for a cursor-responsive weaving artifact that emits recursive ghost pulses, `void-mirror.html` for a seeded pointer field that mirrors your touch with deterministic flares, `radio-echolith.html` for pointer-memory particles with seeded chaos drift and save/copy interactions, `echo-cathedral.html` for a seeded cathedral of pointer-drawn orbits and deterministic traces, `phase-echoes.html` for pointer-evoked phase ghosts that mutate into living loop-choirs, `ether-trellis.html` for a seeded deterministic thread-lattice with pointer-held injection, drift/chaos control, seed-sharing links, and pause/reseed/clear/copy/save interactions, `signal-labyrinth.html` for a saveable phase lattice where seeded labyrinth paths respond to your pointer and pointer-memory noise, and `nocturne-vein.html` for a deterministic pointer field of thread-veins with chaos and seed-link controls, and `pulse-lattice.html` for a deterministic pulse thread lattice with seed controls, pointer pulses, and pause/reseed/copy/save actions.

- `wavelength-rift.html` (`Wavelength Rift`) — seeded pointer field with deterministic seed sharing, pause/rerandomize, pointer sparks, and save/copy actions
- `echo-corridor.html` (`Echo Corridor`) — seeded corridor field with pointer-reactive trajectory bands, density/chaos/speed controls, save-frame, and copy-link sharing
- `clock-hollow.html` (`Clock Hollow`) — pointer-clock chamber with seed persistence, turbulence control, draggable beacons, and PNG/share-link export
- `ghost-thread.html` (`Ghost Thread`) — seeded pointer thread field with reseedable chaos/density controls, draggable thread seeding, copy-share links, and PNG export
- `void-hinge.html` (`Void Hinge`) — seeded particle bridge field with pointer pressure, density/drift/chaos controls, pause/reseed, hash sharing, and frame export
- `pulse-weft.html` (`Pulse Weft`) — deterministic thread-weaving chamber with density/drift/resonance controls, pointer pressure weaving, mode switching, and deterministic share/export controls
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
