# Lucia's Board

A morning/evening organiser dashboard, built as a single static page.
There is no backend — `index.html` contains all of the current schedule,
timetable and settings baked in as data. To change anything, ask Claude
(in the Cowork session this was built in) to update the file and hand you
a fresh copy to commit here.

## Files
- `index.html` — the board itself
- `icon-180.png`, `icon-192.png`, `icon-512.png` — home-screen icons
- `manifest.json` — lets phones/tablets add it to the home screen as an app

## Publishing with GitHub Pages
1. Push this repo to GitHub (create a new repo, then follow the "push an
   existing repository" instructions GitHub shows you).
2. In the repo on GitHub: Settings → Pages → Source → Deploy from branch →
   pick `main` and `/ (root)` → Save.
3. GitHub gives you a URL like `https://<username>.github.io/<repo>/` —
   that's the link to use on Lucia's device and to share with anyone.

## Updating later
1. Ask Claude for the updated `index.html` (and any changed icon/manifest
   files).
2. Replace the files in this folder.
3. `git add -A && git commit -m "Update board" && git push`
4. GitHub Pages redeploys automatically within a minute or two.
