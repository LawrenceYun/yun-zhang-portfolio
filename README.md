# Yun Zhang Portfolio Website

This v14 version makes the photo changes more obvious and forces browser cache refresh.

## Changed

- The homepage circular portrait is visibly larger.
- The portrait image is positioned higher: `object-position: center 24%`.
- The group photo keeps the framed + blurred background design.
- The group photo foreground uses `object-fit: contain`, so the full image is shown.
- The group photo area is controlled in size with `width: min(1080px, 82vw)`.
- `style.css?v=14`, `profile.jpg?v=14`, and `group-photo.jpg?v=14` are used to avoid browser cache showing old versions.

## Upload

Replace these files in your GitHub Pages repository:

- `index.html`
- `style.css`
- `README.md`

If you already uploaded your real photos, do not overwrite them.
