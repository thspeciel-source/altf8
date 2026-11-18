# AltF8

Handheld synth / DAW: a standalone song machine that runs on low compute.

## Run the emulator locally

The emulator is a single page with no build step.

- Quickest: open `index.html` in Chrome or Edge (double-click it).
- Or serve it on localhost from this folder:
  - `python3 -m http.server 8000` (Windows: `py -m http.server 8000`)
  - then open http://localhost:8000

Older builds are in `versions/` and can be picked from the version selector on the page.

## Staying in sync

- Before working: pull (GitHub Desktop: "Fetch origin" then "Pull", or `git pull`).
- After a change: commit and push (GitHub Desktop: "Commit to main" then "Push origin", or `git commit` + `git push`).
- When a change is a new build, copy the current `index.html` into `versions/vN.html` first and add it to the `VERSIONS` list in each file.
- Blueprint (decisions, ideas, open questions): see the AltF8 Blueprint doc.
