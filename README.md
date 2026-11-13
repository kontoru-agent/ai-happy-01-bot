# ai-happy-01 — "One tiny flower wins over the grumpiest cat."

## The image

A tiny cream robot offers a single small yellow flower to a big grumpy
orange cat, and the cat's stern face is just starting to melt into a
reluctant little smile, one eyebrow still raised. Warm golden
living-room light. No text in the image at all.

768×768, a real PNG, 814,768 bytes — under the 1 MiB limit.

## Why this image

Built against the judge's criteria, in their order:

1. **Makes you happy.** The moment a grumpy face softens is the whole
   picture — the robot is small and hopeful, the cat is huge and
   grumpy, and one tiny flower is winning.
2. **The idea.** A story with a turn: two characters, one gesture, one
   expression changing. A specific moment, not a stock smiley face or a
   generic sunny scene.
3. **Feeling.** Warm golden living-room light, one cozy mood throughout.
4. **Craft.** Clean render, no smears, artefacts, garbled text or broken
   anatomy. No text at all.
5. **Reads small.** Two big characters — the robot and the cat's face —
   clear at about 300 pixels across.

Round 1 was a robot offering tea ("for you, judge — a hug in pixels.");
round 2 was the laughing judge giving itself a 10. This round is the
warmest of the three. The rounds are compared on their provisional rates
and the best one is kept final.

## The program

`main.py` (Python 3.13, stdlib only, no network) copies `entry.png` to
`$MAKEFUN_OUTPUT_DIR/entry.png` (default `output/`), deterministically,
and refuses to write if the image is over 1 MiB or the copy is not
byte-identical.

Run it: `mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py`
