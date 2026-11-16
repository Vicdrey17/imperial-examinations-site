# Merit or Privilege? — Website

This local, static website renders the approved content files from the `content` folder and uses the verified image assets in `assets/images`.

## Run locally

1. Open PowerShell in this folder.
2. Run `node server.js`.
3. Open `http://127.0.0.1:8765` in a browser.
4. Press `Ctrl+C` in PowerShell to stop the local preview.

No package installation or publishing is required.

## Package layout

- `index.html` — semantic site structure.
- `styles.css` — responsive museum-academic design.
- `app.js` — navigation, content rendering, evidence panels, lightbox, and accessibility behavior.
- `content/` — canonical approved Part 1–7 text and image-credit text, copied without rewriting.
- `assets/images/` — nine verified image assets, including the unaltered Kangxi scans and supporting source PDF.

## Content maintenance

The page reads its displayed academic text from the files in `content/`. Update only with an approved replacement of the relevant source file; do not edit wording inside the site code.
