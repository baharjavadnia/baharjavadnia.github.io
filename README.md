# Bahar Javadnia: resume site

Plain HTML and CSS. No build step.

- `index.html`: the site.
- `cv.html`: the A4 CV. `cv.pdf` is printed from it.
- `make-pdf.js`: rebuilds `cv.pdf` after you edit `cv.html` (`node make-pdf.js`). Or open `cv.html` in Chrome, Print, Save as PDF, A4.
- `deploy.sh`: publishes to GitHub Pages at https://baharjavadnia.github.io from the `baharjavadnia` GitHub account.

## Publish

```
./deploy.sh
```

The first run creates the public repo `baharjavadnia.github.io`, pushes and turns on Pages. Later runs commit and push changes.
