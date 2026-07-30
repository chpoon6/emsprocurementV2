# EMS Procurement V2 GitHub Pages Fixed Build

This build uses a single self-contained `index.html` with inline CSS and JavaScript.

## Why this fix exists

The GitHub Pages page was rendering as plain HTML because external CSS/JS files were not loading. This self-contained build removes that dependency, so uploading only the root files will work.

## Upload instructions

1. Open this package.
2. Upload `index.html`, `.nojekyll`, and `README.md` to the root of the `emsprocurementV2` repository.
3. Do not upload the ZIP only.
4. Confirm GitHub Pages source is `main` branch and `/root`.

## File structure

```text
emsprocurementV2/
├── index.html
├── .nojekyll
└── README.md
```
