# Neuronwise Labs Website

Static GitHub Pages-ready website for Neuronwise Labs.

## Files

- `index.html` - main homepage
- `styles.css` - shared styling
- `script.js` - lightweight client-side behavior
- `products/learnvanta.html` - smart e-learning product page
- `products/talkena.html` - multilingual AI voice agent product page

## Local preview

You can preview locally with:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## GitHub Pages

This repo is already suitable for GitHub Pages from the root branch:

1. Push the files to `main`
2. In GitHub, open repository settings
3. Under Pages, choose `Deploy from a branch`
4. Select `main` and `/ (root)`

If you want to keep the custom domain, add a `CNAME` file with `neuronwiselabs.com`.
