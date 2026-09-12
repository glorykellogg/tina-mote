# Tina Mote — Quarto website

## Preview and publish

With Quarto installed, open this folder in your editor and run `quarto preview`. Run `quarto render` to create the finished website in `_site/`. Upload the contents of `_site/` to a static website host such as GitHub Pages.

## Edit the site

- `index.qmd`: all visible page content. The content is in a raw HTML block to preserve the preview’s exact layout. Edit the text between the HTML tags; keep the surrounding tags and the opening and closing fences.
- `styles.css`: fonts, colors, spacing, responsive layout, and portrait framing.
- `_quarto.yml`: website settings.
- `template.html`: the page shell and search-engine description.
- `assets/tina-profile.png`: supplied LinkedIn screenshot, displayed as a portrait with CSS clipping. Replace with a standalone headshot when available, and update the `.portrait img` styling to `width:100%;height:100%;object-fit:cover;left:0;top:0`.
- `favicon.svg`: the T browser icon.
