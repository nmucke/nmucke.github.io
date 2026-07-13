# Personal Academic Website

Static HTML and CSS website of Nikolaj T. Mücke, featuring academic background, research, and publications.

## Structure

- `index.html` - Main website
- `css/styles.css` - Styling
- `assets/` - Images and media

## Local Preview

To preview locally without a build step, use Python's built-in HTTP server:

```bash
python3 -m http.server
```

Then open http://localhost:8000 in your browser. Alternatively, open `index.html` directly in your browser.

## Deployment

The site is automatically deployed to GitHub Pages on pushes to the `main` branch using a GitHub Actions workflow (`.github/workflows/static.yml`). No build step or dependencies required.
