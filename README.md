# Witney's Best

A light-hearted, personal awards site celebrating local favourites in Witney.

- `index.html` – the whole site (design and behaviour)
- `data/awards.json` – the awards, edited through Pages CMS
- `photos/` – award photos; uploads from Pages CMS land here
- `.pages.yml` – tells Pages CMS what fields an award has
- `.nojekyll` – tells GitHub Pages to serve the files as they are

To add or edit awards, sign in at https://pagescms.org with your GitHub account,
open this repository and choose **Awards**.

To add a new category, add it to the `values` list in `.pages.yml` and to
`CATEGORY_ORDER` near the top of the script in `index.html`.
