# Midnight Monstera website

Static GitHub Pages website for Midnight Monstera and its first app, **Rooted: Family Chores & Allowance**.

## Files

- `index.html` — studio homepage and Rooted preview
- `styles.css` — shared responsive styles
- `support.html` — support placeholder
- `privacy.html` — privacy-policy placeholder
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

No `CNAME` file is included yet because the final Midnight Monstera domain has not been hard-coded into this package.

When the domain is ready:
1. Enter the custom domain in **Settings → Pages**.
2. Configure the domain's DNS records for GitHub Pages.
3. After DNS resolves, enable **Enforce HTTPS**.
4. GitHub can create/update the repository's `CNAME` file automatically.

## Before public launch

The Privacy and Terms pages are deliberately placeholders. Replace them with policies based on Rooted's final data storage, account model, subscriptions/purchases, child-profile behavior, analytics, and third-party services before release.
