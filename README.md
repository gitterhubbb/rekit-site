# rekit-site

Landing page for Rekit, a Max for Live device that turns a drum stem into a Drum Rack (one pad per sound, loaded with one-shots cut from the stem) and MIDI on Live's grid.

Plain static HTML, served by GitHub Pages from `main` / root. No build step.

- `index.html`: the whole page (CSS and JS inline). The "stem in, pads out" graphic is real Rekit output: two bars of a whole-song extraction (notes from `result.json`, waveform peaks from the stem), embedded as `DATA` in the script.
- `assets/device.jpg`: the device in Live.
- Download: "Coming soon" for now; no release is published.
- `assets/compare.png`, `assets/rack.png`: optional screenshots. Each figure stays hidden until its image exists.

Preview locally:

```bash
python3 -m http.server 8765
```
