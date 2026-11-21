# AltF8

Handheld synth / DAW: a standalone song machine that runs on low compute.

## Run the emulator locally

The emulator is a single page with no build step.

- Quickest: open `index.html` in Chrome or Edge (double-click it).
- Or serve it on localhost from this folder:
  - `python3 -m http.server 8000` (Windows: `py -m http.server 8000`)
  - then open http://localhost:8000

Older builds are in `versions/` and can be picked from the version selector on the page.

Separate lines (a different direction branched from a build, not the next numbered build) also live in `versions/`, for example `versions/sound-first.html`. They keep their own `CURRENT` id and are added to the `VERSIONS` list in every file, just like a build; `index.html` stays the main line.

## Staying in sync (no GitHub Desktop needed)

Pick whichever fits:

- **No install:** on github.com, click **Code > Download ZIP**, unzip, double-click `index.html`. Download again to get the latest.
- **Terminal (git):** once, `git clone https://github.com/thspeciel-source/altf8`. Then `git pull` before working and `git add -A && git commit -m "what changed" && git push` after.
- **Small edits in the browser:** open a file on github.com, click the pencil icon, edit, then **Commit changes**.
- **Through Claude:** ask Claude in a session with this repo attached to make the change; it commits and pushes.

When a change is a new build, copy the current `index.html` into `versions/vN.html` first and add it to the `VERSIONS` list in each file.

Blueprint (decisions, ideas, open questions): see the AltF8 Blueprint doc.

Read by me
