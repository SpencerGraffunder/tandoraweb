# Tandora — Web Build

Web assembly of [Tandora](https://github.com/SpencerGraffunder/Tandora), migrated out of the
[NuclearQuads website](https://github.com/NuclearQuads/nuclearquads.github.io) (`tandora/` directory).

- Live site: https://spencergraffunder.github.io/tandoraweb/
- Build origin: Tandora commit `5d5823ae` (Godot 4 web export, nothreads)
- Served via GitHub Pages from `main` / root. `.nojekyll` is required (the export contains
  files Jekyll would mangle); do not remove it.

## Updating the build

Replace the `index.*` files with the contents of a fresh Godot 4 web export of Tandora
(the export is fully path-relative, so no rewrites are needed). Keep `.nojekyll` and this README.
