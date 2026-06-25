# ideateglobe

Retro pixel-style **World View** globe explorer — a single-page HTML app.

## Run locally

The app needs a local HTTP server (map data is loaded over the network).

```bash
python3 -m http.server 8080
```

Open http://localhost:8080

## Project layout

```
index.html   # UI, styles, globe renderer, and navigation
```

Your original self-contained file (with inline D3, TopoJSON, and world data) can replace `index.html` as-is — no build step required.

## Continue development

- **Cities** — edit the `CITIES` array in `index.html`
- **Look** — CSS variables at the top of the `<style>` block
- **Globe** — `drawBuffer`, `render`, and `COL` in the script section
