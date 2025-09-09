# Bekah’s Bread Collection (v4)

**Tidy structure + robust paths** for GitHub Pages.

## Folder layout
```
/ (repo root)
├── index.html
├── styles.css
└── assets/
    └── img/
        ├── img-0372.jpg
        ├── img-0459.jpg
        ├── img-0700.jpg
        ├── img-1077.jpg
        ├── img-1237.jpg
        ├── img-2607.jpg
        ├── img-8026.jpg
        └── img-8342.jpg
```

## How to deploy
1. Upload **all files and folders** to your repo root (keep this structure).
2. Open `Settings → Pages` → *Deploy from a branch* → Branch: `main` → Folder: `/ (root)`.
3. Visit your Pages URL and hard‑refresh:
   `https://beikabeikaaaaa.github.io/bekahsbread/`
4. Test a direct image URL (should display the image):
   `https://beikabeikaaaaa.github.io/bekahsbread/assets/img/img-0372.jpg`

## Notes
- All image filenames are **lowercase**.
- All `<img>` use explicit relative paths: `./assets/img/...`.
- If you still see 404s, confirm the repo shows those exact files/paths.
