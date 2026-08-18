# DiscoveryGC Markets

A browser-based market dashboard for DiscoveryGC using the public Darkstat API.

## Website

This repository is designed to be hosted with GitHub Pages.

### Publish with GitHub Pages

1. Upload the contents of this folder to the root of a GitHub repository.
2. Open the repository on GitHub.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select **main** and **/(root)**.
6. Click **Save**.
7. GitHub will publish the website at a URL similar to:

   `https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/`

## Files

- `index.html` — the complete DiscoveryGC Markets website
- `.nojekyll` — tells GitHub Pages to serve the files directly
- `README.md` — project and publishing instructions

## Data

The website reads public market data from Darkstat:

`https://darkstat.dd84ai.com`

No Python server or BAT file is required for the GitHub Pages version.

## Notes

GitHub Pages serves the site itself. Darkstat must allow browser cross-origin
requests (CORS) for live API data to load directly from the published website.

## Disclaimer

Unofficial community project. Not affiliated with DiscoveryGC or Darkstat.
