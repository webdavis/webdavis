# CLAUDE

This repo is my public GitHub profile page (`webdavis/webdavis`). Everything in it is
visitor-facing.

## Prose rule

Every change to `README.md` prose, and to any user-visible copy in `assets/*.svg`, must run
through the `humanizer` skill before it is committed. Run the skill, apply its fixes, then
commit. This applies to new copy and to edits of existing copy, no matter how small.

## Layout notes

- `assets/*.svg` are designed banners committed to this repo so GitHub serves them; verify
  render (e.g. `qlmanage`) after editing.
- `stats.json` is machine-written by `.github/workflows/refresh-stats.yml`; do not edit it
  by hand.
