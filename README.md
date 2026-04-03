# Neptune Interactive

Static page for Neptune’s characteristics (HTML/CSS/JS). [Standards.md](Standards.md) holds curriculum and integration notes.

**Live:** https://content-interactives.github.io/Neptune

## Development

```bash
npm run dev
```

Runs `npx http-server -p 8082` per `package.json`. Browse to the served root and open `index.html`.

Alternatively: `npx serve .` from the repo root.

## Layout

- `index.html` — entry  
- `Flexi_Telescope.svg` and other assets referenced by the page

There is no `src/` or `public/` build tree; the former README’s paths referred to a different layout.

## Stack

Static HTML, CSS, JavaScript.

## Deployment

Copy the static files to GitHub Pages.
