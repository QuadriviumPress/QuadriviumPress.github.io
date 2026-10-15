# Quadrivium Press

Organization landing page for [quadriviumpress.com](https://quadriviumpress.com/). The site is static HTML (`index.html`), with `CNAME` pointing the apex domain at GitHub Pages.

The marked catalog section is generated from `bindery/structure/repos.json`.
From the fleet root, run `python3 bindery/scripts/generate-discovery.py` after
changing book metadata, then commit the updated `index.html` here. The same
command updates the organization profile so both catalogs use matching links.
