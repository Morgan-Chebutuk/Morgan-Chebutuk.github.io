# Morgan-Chebutuk.github.io

My personal portfolio — live at **https://morgan-chebutuk.github.io**

A single-page, dependency-free static site: hand-written HTML, CSS, and vanilla JavaScript.
No build step, no framework, no bundler. Deployed straight from `main` by GitHub Pages.

## Structure

```
.
├── index.html                    # all page content
├── styles.css                    # design tokens + layout (dark theme, responsive)
├── script.js                     # nav, scroll header, reveal-on-scroll
├── Morgan-Chebutuk-Resume.pdf    # linked from the hero, nav, and contact section
└── .nojekyll                     # serve files as-is, skip Jekyll processing
```

## Local preview

Open `index.html` in a browser, or serve it:

```bash
python -m http.server 8000
# or
npx serve .
```

Then visit http://localhost:8000

## Editing

- **Text and projects** — `index.html`. Each project is one `<article class="project">` block; copy one to add another.
- **Colors, spacing, fonts** — the `:root` custom properties at the top of `styles.css`.
- **Featured project** — add `featured` to a project's class list to give it the full-width treatment.
- **Resume** — replace `Morgan-Chebutuk-Resume.pdf` in place; the filename is referenced in three spots, so keep the name.

Pushing to `main` redeploys the site automatically.

## Contact

- kimasetm@gmail.com
- [LinkedIn](https://www.linkedin.com/in/morgan-kimaset-chebutuk-65a146262)
- [GitHub](https://github.com/Morgan-Chebutuk)
