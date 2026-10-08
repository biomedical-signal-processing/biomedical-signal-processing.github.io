# Luigi Fiorillo — personal research website

A lightweight, responsive portfolio for GitHub Pages. Built with plain HTML, CSS, and a small navigation script; there is no build step or package installation.

## Preview locally

Open `index.html` in a browser, or serve the directory with:

```sh
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Publish on GitHub Pages

1. Create a new public repository in your GitHub account. Name it `biomedical-signal-processing.github.io` if you want the site at the account root, or choose any repository name for a project URL.
2. Push the files in this directory to the repository's `main` branch.
3. In the repository, open **Settings → Pages**. Under **Build and deployment**, select **GitHub Actions**. The included workflow deploys the site on each push to `main`. If the initial push ran before Pages was enabled, rerun the workflow from the Actions tab.
4. GitHub will show the live URL on the same settings page after the first deployment.

All assets use relative paths, so the site works both at an account root and under a project path. The `.nojekyll` file keeps GitHub Pages from processing the static files with Jekyll.

## Editing

Content and links are in `index.html`. Styling is in `styles.css`; the mobile menu is in `script.js`. The portrait and profile content came from `CV-sleep-research.tex` in the supplied CV archive. See `CONTENT-SOURCES.md` for content provenance.
