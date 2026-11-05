# dance-figure-trainer

Tap-to-advance trainer that shows dance figures (random or in list order, each one once per round). Implemented as single static HTML+JavaScript page, built for phones in portrait.

Open it on https://mshekow.github.io/dance-figure-trainer/

Settings:
- figure list
- whether to show 1 or 2 figures
- order: random, or as listed
- number of figures to use (0 = all; random subset, or the first n when listed)
- max font size

which are stored in your browser. The chosen subset is not stored; it is redrawn on page load.

Buttons:
- Restart: start over with the same subset
- New set: draw a new random subset (disabled when it would make no difference)
