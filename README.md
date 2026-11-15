# Praveen Sakthi — Portfolio

Static portfolio site. No build step.

## Run locally

```bash
python3 -m http.server 8812
```

Then open http://localhost:8812

## To fill in

- Photo: replace `assets/hero-photo-bw.webp` (grayscale) and `assets/hero-photo-colour.webp` (color), 801×1033 cutouts with a transparent background. Card photo: `card/win_sub.webp`.
- Projects: edit the `PROJECTS` list in `web-developer/`, `app-developer/` and `ui-ux-designer/` `index.html`, and `WORLDS` in `graphic-designer/index.html`.
- Story placeholders (university, analyst role details) in `index.html`.

## Deploy on Render

This repo includes `render.yaml`. In Render: **New → Blueprint**, pick this repo, and apply.
Or **New → Static Site** with an empty build command and publish directory `.`.
