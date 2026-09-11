# Morgan-Chebutuk.github.io

My personal portfolio — live at **https://morgan-chebutuk.github.io**

A single-page, dependency-free static site: hand-written HTML, CSS, and vanilla JavaScript.
No build step, no framework, no bundler. Deployed straight from `main` by GitHub Pages.

## Structure

```
.
├── index.html    # main page content
├── resume.html   # web resume (print stylesheet included)
├── styles.css    # design tokens + layout (dark theme, responsive)
├── resume.css    # resume page styles + print rules
├── script.js     # nav, scroll header, reveal-on-scroll
└── .nojekyll     # serve files as-is, skip Jekyll processing
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
- **Resume** — `resume.html`. This web copy deliberately omits phone number and mailing address; keep it that way. Use the "Print / Save as PDF" button for a clean printed version.

Pushing to `main` redeploys the site automatically.

## Contact

- kimasetm@gmail.com
- [LinkedIn](https://www.linkedin.com/in/morgan-kimaset-chebutuk-65a146262)
- [GitHub](https://github.com/Morgan-Chebutuk)
