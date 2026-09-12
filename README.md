# Tina Mote — Quarto website

This standalone project adapts Glory Kellogg’s serif typography, ivory background, and simple professional layout for Tina Mote.

## Preview and publish

With Quarto installed, open this folder in your editor and run `quarto preview`. Run `quarto render` to create the finished website in `_site/`. Upload the contents of `_site/` to a static website host such as GitHub Pages.

## Edit the site

- `index.qmd`: all visible page content. The content is in a raw HTML block to preserve the preview’s exact layout. Edit the text between the HTML tags; keep the surrounding tags and the opening and closing fences.
- `styles.css`: fonts, colors, spacing, responsive layout, and portrait framing.
- `_quarto.yml`: website settings.
- `template.html`: the page shell and search-engine description.
- `assets/tina-profile.png`: supplied LinkedIn screenshot, displayed as a portrait with CSS clipping. Replace with a standalone headshot when available, and update the `.portrait img` styling to `width:100%;height:100%;object-fit:cover;left:0;top:0`.
- `favicon.svg`: the T browser icon.

## Content notes

Professional history and education come from the supplied LinkedIn screenshots. The research focus and Ed.D. confirmation were supplied separately by Glory. The doctorate is marked in progress. The screenshots show only two of three education entries, so the unseen entry is omitted. No publications, courses, personal email address, or completed doctorate have been invented.

The rendered website is also available in the separate `tina-mote-site/dist` folder. The website HTML was previewed locally. A full Quarto render could not be verified here because Quarto could not open its local cache database.

The Performance review section contains 22 quoted words in total, excerpted from anonymous Rate My Professors reviews dated January 22, 2026; January 9, 2026; and December 17, 2025. Source: https://www.ratemyprofessors.com/professor/2229445#ratingsList

Tenured Faculty title and email verified in Triton College’s Mathematics directory: https://www.triton.edu/about/dept/academic/arts-and-sciences/mathematics.html
Rate My Professors displayed 4.9/5 based on 55 student ratings and 100% would take again when checked September 12, 2026. These are dated static values; update them manually as reviews change.
