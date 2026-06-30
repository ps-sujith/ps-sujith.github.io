# ps-sujith.github.io

Personal portfolio site for **Sujith PS** — Senior Android Developer.

Live at [ps-sujith.github.io](https://ps-sujith.github.io)

## About

A single-page portfolio built with plain HTML, CSS and JavaScript — no build tools or
frameworks. It covers experience, projects, tech stack and contact details, and is
deployed straight from this repo via GitHub Pages.

## Structure

```
.
├── index.html         # The entire site (markup, styles, script)
├── logos/              # Company logos and project screenshots
└── sujith_resume.pdf   # Downloadable CV
```

## Running locally

Since it's a static site, just open `index.html` in a browser, or serve it locally:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deployment

The site is served directly from this repository via [GitHub Pages](https://pages.github.com/).
Pushing changes to the default branch updates the live site automatically.
