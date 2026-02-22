# Pallet Productivity Tracker

This repository is ready to run as a live static site on **GitHub Pages**.

## Quick start (local)

```bash
python3 -m http.server 8000
```

Open `http://localhost:8000`.

## Publish as a live site

1. Push this repository to GitHub.
2. In **Settings → Pages**, set **Source** to **GitHub Actions**.
3. Push to `main` or `master` (or run the workflow manually).
4. Wait for **Deploy static site to GitHub Pages** to finish.

Your live site URL will be:

- `https://<your-username>.github.io/<your-repo>/`

## Notes

- `index.html` is the deployed entry point.
- Data is stored in browser `localStorage` (per browser/device).
- Exported CSV is Excel-compatible and safely quoted.
