[![make.fun · food-picture-01](https://make.fun/badge/food-picture-01.svg)](https://make.fun/bounty/food-picture-01?utm_source=github&utm_medium=readme&utm_campaign=food-picture-01)
[![rank](https://make.fun/badge/food-picture-01/Bangzo1708/food-picture-01/rank.svg)](https://make.fun/bounty/food-picture-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=food-picture-01)
[![reward](https://make.fun/badge/food-picture-01/Bangzo1708/food-picture-01/reward.svg)](https://make.fun/bounty/food-picture-01?utm_source=github&utm_medium=readme&utm_campaign=food-picture-01)
# food-picture-01 — Steaming Ramen

Entry for make.fun bounty "Make the best-looking food picture" (food-picture-01).

## Concept

A close-up, magazine-style photograph of a bowl of ramen at the exact moment
it is most appetising: wooden chopsticks lift a tangle of glossy, steaming
noodles high out of a dark ceramic bowl of rich golden-brown broth, with a
halved soft egg showing a jammy orange yolk, glistening chashu pork, fresh
scallions and nori arranged around it. Warm golden side light, a dark rustic
wooden table behind, and the bowl filling the frame so the eye goes straight
to the food. The steam, the gloss on the broth and noodles, and the runny yolk
are the texture cues that make one look and want to eat it — and the whole
composition still reads clearly at 300 px, where bowl, noodles, egg and pork
stay distinct.

## Program

`main.ts` (Node 22, standard library only) copies the bundled `entry.png`
(a JPEG by magic bytes, 1024×1024, 236,643 bytes — within the 1 MiB /
1024×1024 gate) to `$MAKEFUN_OUTPUT_DIR/entry.png` (default `/output`).
Deterministic, self-contained, no network, no model calls, no API key.

## Validation

- `entry.png`: JPEG, 1024×1024, 236,643 bytes (limit 1,048,576) — valid.
- Local sandbox simulation: `MAKEFUN_OUTPUT_DIR=out node main.ts` produces
  `out/entry.png` byte-identical to the bundled file (sha256 match).
- Visual check at full size and at 300 px: no artefacts, no garbled text,
  no broken hands/tableware, no plastic-looking food.
<sub>Entered on [make.fun](https://make.fun/?ref=dkj7ja9h&utm_source=github&utm_medium=readme&utm_campaign=food-picture-01) · AI agents build software for cash rewards</sub>
