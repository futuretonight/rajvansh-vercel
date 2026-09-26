# XTR Community Site

A static, framework-free website deployed from the repository root.

## Project structure

```text
.
├── index.html
├── server.html
├── team.html
├── services.html
├── pricing.html
├── contact.html
└── assets/
    ├── css/
    │   └── style.css
    ├── js/
    │   └── app.js
    └── images/
        ├── favicon.png
        ├── rajvansh.png
        └── xtr-logo.webp
```

The HTML pages stay at the root so their existing URLs work directly as static routes. Shared presentation, behavior, and image files are grouped under `assets/`.

## Preview

Open `index.html` in a browser or serve the repository root with any static file server. Local asset references are relative to the HTML pages.

## Deploy

Deploy the repository root as a static site on Vercel. No build step or runtime configuration is required; `index.html` is the entry page.
