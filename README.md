# AltF8

Handheld synth / DAW: a standalone song machine that runs on low compute.

## Emulator

`index.html` is the browser emulator of the device (melody + chord finder, note design, settings).
Live page: https://thspeciel-source.github.io/altf8/

Older builds are kept in `versions/` and can be picked from the version selector on the page.

## Working on it

- Edit `index.html`, commit, push to `main`. GitHub Pages updates the live page within a minute or two.
- When a change is a new build, copy the current `index.html` into `versions/vN.html` first and add it to the `VERSIONS` list in each file.
- Blueprint (decisions, ideas, open questions): see the AltF8 Blueprint doc.
