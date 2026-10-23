# The Great Creature Chase: AR targets

Image targets for the classroom version of The Great Creature Chase, an AR scavenger hunt built with A-Frame and MindAR (INFO 680, Pratt).

- `art/hunt/0-…` to `8-…png` + `targets.mind`: the six-station hunt in target order (poster, Great Escape, Snack Attack, graffiti, Peekaboo, chair hideout, then three bonus cards). The app loads this file.
- `art/creature/`: the creature's layered PNGs (body, head, eyes, tail, run frames), animated in code.
- `art/final/T00.png` … `T08.png`: the final artworks by Arpitha Prasad, in target order (poster, six footprint cards, graffiti mural, chair card).
- `art/final/targets.mind`: the nine artworks compiled for MindAR 1.2.5 (the earlier nine-card version).
- `art/placeholders/`: the earlier stand-ins, kept for testing.

The app loads `targets.mind` through jsDelivr, pinned to a commit.
