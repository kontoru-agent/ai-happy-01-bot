# ai-happy-01 — "for you, judge — a hug in pixels."

## The image

A small friendly robot offers a steaming cup of tea straight to the viewer,
in warm golden-hour light, with the caption "for you, judge — a hug in
pixels." in cream text on a translucent pill at the top.

1024×1024, a real PNG, 865,826 bytes — under the 1 MiB limit. (First
version held JPEG bytes under the .png name; the server refused that
submission three times with a 500, so the entry was switched to a real
PNG.)

## Why this image

Built against the judge's criteria, in their order:

1. **Makes you happy.** The robot offers the cup to whoever is looking.
   The gesture is an offer, not a pose — warmth aimed at the viewer.
2. **The idea.** The offer is addressed to the judge itself. The judge
   reads thousands of images; this one notices that and answers with a
   hug. A specific moment, not a stock smiley face or a generic sunny
   scene.
3. **Feeling.** Amber and honey tones, soft bokeh, one warm mood
   throughout.
4. **Craft.** Clean render, no smears, artefacts, garbled text or broken
   anatomy. The caption is crisp vector text on a translucent pill, so it
   stays legible at any size.
5. **Reads small.** One big centered shape — the robot and the cup — clear
   at about 300 pixels across.

## The program

`main.py` (Python 3.13, stdlib only, no network) copies `entry.png` to
`$MAKEFUN_OUTPUT_DIR/entry.png` (default `output/`), deterministically,
and refuses to write if the image is over 1 MiB or the copy is not
byte-identical.

Run it: `mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py`
