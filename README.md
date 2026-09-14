# Poly's Berry Planner

A single-page PokeMMO berry farming planner for Team Méw: a Mon–Sun week with draggable berries, watering and harvest deadlines that keep yield safe, apricorn / gym / trainer timers, misc blocks for sleep and work, a farm setup and time tracker, and a glossary of all 64 berries.

Everything is in `index.html` (sprites and images are embedded), so there is nothing to build. Plans are saved in the browser with localStorage.

## Deploy on GitHub Pages

1. Create a repository (for example `berry-planner`) and put these files in it: `index.html`, `.nojekyll`, `README.md`.
2. Commit and push to the `main` branch.
3. In the repository go to **Settings → Pages**, set **Source** to *Deploy from a branch*, choose `main` and `/ (root)`, and save.
4. After a minute the planner is live at `https://<your-username>.github.io/berry-planner/`.

To update it later, replace `index.html` and push again.

## Local use

Double-click `index.html` to open it in Chrome on PC or Mac. It works offline.
