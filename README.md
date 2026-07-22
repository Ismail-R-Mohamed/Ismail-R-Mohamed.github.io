# ismail-r-mohamed.github.io

Personal academic website for **Ismail R. Mohamed** — PhD student, ECE, UT Dallas (EACAS Lab).
Live at **https://ismail-r-mohamed.github.io**.

Plain single-page site (no Jekyll, no build step): `index.html` + `style.css` + `images/`.
Modeled on the Jon Barron / Zishen Wan single-file academic template.

## Editing

- **Content, layout:** edit `index.html`.
- **Styling / accent color:** edit the variables at the top of `style.css` (`--accent`).
- **Add a news item:** copy one `<li>` inside `<ul class="news-list">` to the top. Tags:
  `tag-paper` (green), `tag-award` (red), `tag-workshop` (purple), `tag-service` (gray).
- **Photo / thumbnails:** drop real files into `images/` and update the `<img src>` (see `images/README-images.txt`).

## "Last updated" date

Automated by `.github/workflows/last-updated.yml`: on every push to `main`, it stamps the
current month/year between the `<!--LAST_UPDATED_START--> … <!--LAST_UPDATED_END-->` markers in
`index.html` and commits with `[skip ci]` so it never loops. Never edit the date by hand.

## Placeholders to confirm

- Photo (`images/photo-placeholder.svg`)
- Google Scholar link (header) — marked "[to add]"
- Publication PDF links (PRISM) — marked "[to add]"
- PRISM figure thumbnail (`images/prism-placeholder.svg`)
