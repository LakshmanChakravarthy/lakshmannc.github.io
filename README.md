# Personal site — draft v1

Plain HTML/CSS/JS, no build step. Designed to be hosted directly on GitHub Pages.

## Structure
```
index.html      → all page content
css/style.css   → all styling (design tokens at the top)
js/main.js      → mobile nav toggle + footer year (that's it)
assets/         → put cv.pdf and any images here
```

## Deploy on GitHub Pages
1. Create a repo, e.g. `yourusername.github.io` (for a root domain) or any name (served at `yourusername.github.io/reponame`).
2. Push these files to the repo's `main` branch.
3. In the repo: **Settings → Pages → Source → Deploy from branch → main → / (root)**.
4. Site goes live at the URL GitHub shows you (may take a minute).

## Placeholders to fill in before publishing
- [ ] Your surname in `<title>`, nav brand, and footer copyright
- [ ] Real email address (currently `you@example.edu`)
- [ ] Google Scholar / GitHub / LinkedIn links (currently `#`)
- [ ] `assets/cv.pdf` — add file once your CV is updated; the download button already points here
- [ ] Postdoc availability line in the footer ("Available from ...")
- [ ] Research vision paragraph — currently drafted from what I know of your framing; rewrite in your own voice
- [ ] Publications list — years/authors/exact venue formatting need your input
- [ ] Paper/code links for each project (currently `#`)
- [ ] Optional: add a photo to the hero if you want one (currently text-only)

## Notes on the design
- Signature element: the small "primitives → composition" diagram in the hero and next to each project, echoing the actual research content.
- Status tags (published / accepted / ongoing) use a small color-coded mono label — easy to update as projects progress.
- Layout is editorial (a list of project entries), not a card grid — reads as depth rather than decoration to a hiring committee.
