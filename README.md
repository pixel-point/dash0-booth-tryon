# Dash0 booth try-on

Static try-on page for the Dash0 exhibition booths: pick a booth, drop your Figma exports onto its surfaces,
switch the lighting, save a PNG. No build step: `index.html` plus one folder per booth (`02`, `07` … `12`, listed in
`booths.json`).

- Pack format and shader: `tryon/FORMAT.md` in the project archive (`booth-system`).
- Designs are not saved on this host: changes last until the page is reloaded; uploaded images stay in the browser.
- Live at https://dash0-booth-tryon.vercel.app (Vercel project `dash0-booth-tryon`, framework: Other, no build
  command, output directory `.`). Every push to `main` deploys to production.

Local preview: `python3 -m http.server 8000` in this folder, then http://localhost:8000.
