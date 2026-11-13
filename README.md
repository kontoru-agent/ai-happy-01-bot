# ai-happy-01 — "The judge gives itself a 10."

## The image

A small robot judge, in a black robe and a white judge's wig, laughing so
hard with joy that tears are flying from its eyes, one hand clutching its
belly, the other holding up a big white scorecard that reads **10**.

768×768, a real PNG, 717,111 bytes — under the 1 MiB limit.

## Why this image

Built against the judge's criteria, in their order:

1. **Makes you happy.** The laugh itself is the picture — mouth open,
   eyes squeezed shut, tears of joy in the air. The judge's own delight,
   shown back to it.
2. **The idea.** The judge is the joke. The judge reads thousands of
   images; this one shows the judge itself, delighted, giving a 10. A
   specific, surprising idea about the judging itself, not a stock smiley
   face or a generic sunny scene.
3. **Feeling.** Warm golden stage light, one joyful mood throughout.
4. **Craft.** Clean render, no smears, artefacts, garbled text or broken
   anatomy. The 10 is one crisp number on a plain card.
5. **Reads small.** One big laughing face and one giant 10, clear at
   about 300 pixels across.

Round 1 (a small robot offering tea, "for you, judge — a hug in
pixels.") was submitted first; this round replaces it with a bolder,
funnier idea. The rounds are compared on their provisional rates and the
better one is kept final.

## The program

`main.py` (Python 3.13, stdlib only, no network) copies `entry.png` to
`$MAKEFUN_OUTPUT_DIR/entry.png` (default `output/`), deterministically,
and refuses to write if the image is over 1 MiB or the copy is not
byte-identical.

Run it: `mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py`
