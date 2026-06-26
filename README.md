# Arif H. Rezaldy — Portfolio

Personal portfolio site for Arif H. Rezaldy, Senior Engineering Manager.

## Overview

A single-page, dependency-free static website. No build step, no frameworks —
just HTML, CSS, and a small amount of vanilla JavaScript.

## Project structure

```
index.html            Main page
favicon.ico           Site icon
resource/
├── styles.css        All styles
├── script.js         Interactions (scroll reveal, nav, footer year)
├── fonts/            Self-hosted fonts (woff2) + fonts.css
└── images/           Profile photo and company logos
```

## Running locally

Because it is plain static files, just open `index.html` in a browser. If you
need a local server (e.g. for testing on a phone), any static server works:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deployment

This is a plain static site, so it can be deployed easily from the `master`
branch. Pushing to `master` publishes the latest version.

## License

See [LICENSE](LICENSE).
