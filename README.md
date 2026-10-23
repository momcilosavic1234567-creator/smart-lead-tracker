# Smart Lead Tracker

Smart Lead Tracker is a small portfolio project built with plain HTML, CSS, and JavaScript. This first milestone establishes a responsive dashboard layout and GitHub Pages deployment workflow.

## Project files

- `index.html` — accessible page structure and dashboard cards
- `style.css` — visual styling and responsive layout
- `app.js` — JavaScript entry point and initial DOM checks
- `.github/workflows/pages.yml` — deploys the static site to GitHub Pages on pushes to `main`

## Run locally

Open `index.html` in a browser. Press `F12` and open the Console; it should show `Smart Lead Tracker loaded successfully.` and the dashboard elements.

## GitHub Pages deployment

1. In repository **Settings → Pages**, set **Build and deployment → Source** to **GitHub Actions**.
2. Open the **Actions** tab and select **Deploy static site to GitHub Pages**.
3. Run the workflow if it has not started automatically, or push another commit to `main`.
4. Wait for the workflow to finish successfully. The deployment URL will appear under **Settings → Pages** and in the workflow's deployment environment.

## Current milestone and limitations

This is the dashboard shell only. Lead creation, changing status, searching, and browser storage are not implemented yet; the statistics currently remain at zero. These will be added as later milestones and tested before being described as functional.

GitHub Pages is public. Do not add passwords, tokens, or actual customer information to this portfolio demo.
