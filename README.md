# Green Value Group Public Portfolio

## Release

`public-showcase-v0.8.0`

## What changed in v0.8.0

- Removed fragile inline project-card click handlers.
- Added delegated click handling for project cards and buttons.
- Added visible project-data loading and error status.
- Added Priority Opportunities section.
- Added audience paths for experts, institutions, sponsors and investors/JV partners.
- Added support packages.
- Added evidence library.
- Added `whyNow`, `evidenceLevel` and `supportPackageFit` project fields.
- Strengthened the public disclaimer.
- Improved Guzo Charge positioning as a conditional, validation-ready EV charging opportunity.

## File structure

- `index.html` — application shell and public dashboard logic
- `data/projects.json` — public project data
- `docs/guzo-charge/` — Guzo Charge public evidence files
- `EDIT_PROJECTS.md` — safe editing guide
- `.nojekyll` — GitHub Pages compatibility

## GitHub Pages update

Upload or replace all files from this package at the repository root. Confirm the project data path is:

`/data/projects.json`

Do not upload the folder itself as a subfolder.
