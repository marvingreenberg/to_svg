# to_svg
Simple example of some png or jpeg to SVG code

## Primitive now, assumes python familiarity

Usage:

* python3 -m venv .venv; source .venv/bin/activate
* pip install -r requirements.txt
* python3 to_svg.py

Notes: inside and outside paths are just generated as
separate paths, so would need to be joined in some other
tool (like the white part of the eyes.)

This just converts the existing simple-panda.png into a
an SVG simple-panda.svg

The code seems to work fine for png or jpeg files.
