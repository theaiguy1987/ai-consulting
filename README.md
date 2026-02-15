# AI Consulting Landing Page

Static site for the AI automation training / consulting flyer.

## Structure

- `index.html` - main page
- `styles.css` - styles
- `Images/` - images used by the page

## Preview locally

Open `index.html` directly, or run a local server:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Publish on GitHub Pages

1. Push to the default branch (currently `master`).
2. In GitHub: **Settings → Pages**
3. Under **Build and deployment** choose:
   - **Source:** Deploy from a branch
   - **Branch:** `master`
   - **Folder:** `/ (root)`

GitHub will show the published URL in the Pages section once it is live.
