# Deep Sleep — Ambient Sound Mixer

A rebuilt version of navneet-20/sleep designed for GitHub Pages.

## Why this rebuild
The original project loads Tone.js and expects MP3 files in `assets/`. The UI also contains legacy Firebase boilerplate. The new version removes those runtime dependencies and uses the browser Web Audio API to generate the ambient layers locally.

## Features
- Reliable Start Audio flow for browser autoplay restrictions
- 12 ambient sound layers
- Individual volume controls
- Master volume
- Play/pause and Stop All
- Sleep timer
- LocalStorage mix persistence
- Mobile responsive
- No backend
- No external audio files
- Works as a static GitHub Pages site

## Deploy
Replace the contents of the repository with `index.html` and push to the `main` branch. GitHub Pages can then serve the repository root.

## Important
Generated ambience is intentionally lightweight and loop-free. For higher-fidelity recordings such as realistic rain, waves, or fireplace audio, royalty-free audio assets can be added later without changing the UI architecture.
