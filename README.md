# Midnight Monstera website

Static GitHub Pages website for Midnight Monstera, LLC and its apps, **Knewly: Simple Flashcards** and **Rooted: Family Chores & Allowance**.

## Files

- `index.html` — studio homepage and app previews
- `styles.css` — shared responsive styles
- `support.html` — public support contact
- `privacy.html` — studio privacy-policy index
- `knewly/privacy/index.html` — current Knewly privacy policy
- `terms.html` — terms placeholder
- `assets/midnight-monstera-horizontal.jpg` — supplied horizontal logo
- `assets/midnight-monstera-vertical.jpg` — supplied vertical logo
- `assets/rooted-icon.jpg` — supplied Rooted app icon
- `.nojekyll` — tells GitHub Pages to serve the site as plain static files

## Preview locally

Double-click `index.html`, or from this directory run:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Publish with GitHub Pages

If you already have a GitHub Pages repository, replace its current website files with the contents of this folder.

For a new repository:

1. Create a public GitHub repository.
2. Put **the contents of this folder** in the repository root.
3. Commit and push to `main`.
4. Open **Repository → Settings → Pages**.
5. Under **Build and deployment**, select **Deploy from a branch**.
6. Choose `main` and `/ (root)`, then save.
7. GitHub will show the temporary `github.io` URL after the deployment finishes.

## Custom domain

The site is published at `https://midnightmonstera.com` using the tracked `CNAME` file and GitHub Pages.

## Before public launch

Knewly's privacy policy is published as a pre-release draft at `https://midnightmonstera.com/knewly/privacy/`. Keep the page synchronized with the app's implementation and remove its draft notice only after the release-readiness items in the notice are complete. The Terms page and Rooted privacy policy remain placeholders that must be finalized before the applicable public release.
