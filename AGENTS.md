# AGENTS.md

## Cursor Cloud specific instructions

This is a static single-page website (HTML/CSS/JS, no build tools or package manager).

### Running the site
- Serve locally: `python3 -m http.server 8080` from the repo root, then open `http://localhost:8080/index.html`.
- No build step, no linter, no test framework configured.
- The portrait image is referenced as `photo.jpg` in the same directory as `index.html`.

### Notes
- The site uses Google Fonts (Inter) loaded via CDN — requires internet access.
- All styles and scripts are inlined in `index.html`; no external CSS/JS files.
- The update script is a no-op (`echo "No dependencies to install"`) since there are no installable dependencies.
