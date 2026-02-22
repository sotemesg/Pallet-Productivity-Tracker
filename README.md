# Pallet Productivity Tracker (Live Site Ready)

This project is now configured as a static site that can be published directly with **GitHub Pages**.

## Run locally

Open `index.html` in a browser, or serve it from a local web server:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deploy as a live site on GitHub Pages

1. Push this repository to GitHub.
2. Ensure your default branch is `main` (or update `.github/workflows/deploy-pages.yml` if needed).
3. In your GitHub repository, open **Settings → Pages** and confirm **Source = GitHub Actions**.
4. Push to `main`.
5. The workflow **Deploy static site to GitHub Pages** publishes the site.

After the workflow succeeds, your live URL will be available in the workflow output and under the repository's Pages settings.

## Files

- `index.html` → live site entry point.
- `pallet_tracker.html` → original standalone file kept for reference.
- `.github/workflows/deploy-pages.yml` → automated deployment workflow.
