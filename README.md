# Partou Component Inventory

A site inventory of https://partou.nl/: 54 captured pages and 25 components, each with a screenshot.

**Browse it:** https://roandeighton.github.io/partou-inventory/

## What's in here

- `content/`: the written inventory (overview, one file per component, one per page). Markdown.
- `pages/<slug>/`: the captured screenshot (`screenshot.webp`), saved HTML and cropped component images for each page.
- `manifest.json`: what was captured, when, and which version of the tool did it.
- `analysis.json`: the detected page templates and components the content was written from.

The website is built from this data and lives on the `gh-pages` branch. That branch is replaced on every publish, so edit the files on `main`.

Made with the site inventory tool, commit `b6b4200`.
