# Bekah’s Bread Collection — Root Image Layout

This patch matches your current repository structure at:
https://beikabeikaaaaa.github.io/bekahsbread/

## What changed
- Images are placed at the **repo root** (e.g. `IMG_0372.jpg`) instead of `assets/img/`.
- `index.html` now uses root-relative paths like `./IMG_0372.jpg`.

## Upload steps
1. Replace the files in your repo with the ones from this ZIP:
   - `index.html`
   - `styles.css`
   - `IMG_0372.jpg` … `IMG_8342.jpg`
2. Keep your repository name and GitHub Pages settings as-is.
3. Force-refresh the site and test an image directly, for example:
   `https://beikabeikaaaaa.github.io/bekahsbread/IMG_0372.jpg`

If you prefer a tidy structure later, we can move images to `assets/img/` and update paths.
