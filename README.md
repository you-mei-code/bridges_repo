# bridges_repo — GitHub Pages site

This commit adds a minimal static site in the `docs/` folder so the repository can be served with GitHub Pages.

How to publish:

1. In the repository on GitHub, go to Settings → Pages.
2. Under "Source", select "Deploy from a branch", choose `main` and the `/docs` folder.
3. Save. The site will publish soon at `https://you-mei-code.github.io/bridges_repo/` (or at a custom domain if configured).

Files added:
- `docs/index.html` — site entry point
- `docs/style.css` — minimal styling

If you prefer a different setup (Jekyll, GitHub Actions workflow, or a dedicated `gh-pages` branch), tell me and I will add it.
