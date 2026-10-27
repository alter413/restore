# TON Username

Static, local-first vanity address generator for TON. The UI is served as plain HTML/CSS/JS and is ready for GitHub Pages.

## Run locally

```bash
python -m http.server 4173
```

Open `http://localhost:4173`.

## GitHub Pages

The repository includes `.github/workflows/pages.yml`. In GitHub, open **Settings → Pages**, choose **GitHub Actions** as the source, and the workflow will publish the root site on every push to `main`.

The browser app keeps the seed phrase in memory and creates a JSON backup only when the user clicks the download button. Always verify a generated address in the wallet you intend to use before sending funds.

