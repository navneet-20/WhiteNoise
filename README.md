# Deep Sleep — High Quality Asset Audio Version

The generated sounds have been removed completely. This version plays your own audio files from `assets/`.

## Expected structure

sleep/
- index.html
- assets/
  - rain.mp3
  - ocean.mp3
  - wind.mp3
  - fire.mp3
  - thunder.mp3
  - forest.mp3
  - fan.mp3
  - brown-noise.mp3
  - pink-noise.mp3
  - night.mp3
  - train.mp3
  - cafe.mp3

If your filenames differ, edit the `file:` values near the top of `index.html`.

The files loop automatically and are mixed through the browser Web Audio API. Use MP3/WAV files for best results. GitHub Pages paths are case-sensitive.
