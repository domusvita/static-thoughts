# static-thoughts

Minimal static site designed for GitHub Pages.

## Local preview

Open `index.html` directly in your browser, or run a tiny static server:

```bash
python3 -m http.server 8000
```

Then visit http://localhost:8000

## Publish with GitHub Pages

1. Push this repository to GitHub.
2. In your repository settings, open **Pages**.
3. Under **Build and deployment**, choose:
   - **Source**: Deploy from a branch
   - **Branch**: `main` (or your default branch)
   - **Folder**: `/ (root)`
4. Save.
5. Wait about 1 minute, then open the published URL shown in the Pages settings.
