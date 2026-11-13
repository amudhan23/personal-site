# amudhan23.github.io · personal site

Single-file portfolio for Amudhan Muthaiah. No build step: `index.html` carries all CSS and JS.
Fonts from Google Fonts, GSAP 3.12 from cdnjs. The hero background is a generative *kolam* drawn on a canvas.

## Edit
Everything is in `index.html`, in section order: hero → ticker → about → work → experience → research → education → notes → contact.
Project cards are `<article class="pcard" data-cat="zk chain ai systems">`; the `data-cat` values drive the filter chips.
Notes are `<div class="ncard" data-tags="...">` blocks; add a new one by copying an existing card.

## Deploy
GitHub Pages: Settings → Pages → Source: `main` / root. Or drop the folder on Vercel/Netlify.
