# Agentify landing page

Static site for agentify. One `index.html`, no build step. Deployed on GitHub Pages.

## Setup (once)

1. **Formspree** — the demo form needs somewhere to send submissions.
   - Go to https://formspree.io, sign up with mohika591@gmail.com, click **New form**.
   - Copy the form ID from the endpoint it gives you (`https://formspree.io/f/abcdwxyz` → `abcdwxyz`).
   - In `index.html`, replace `YOUR_FORM_ID` with that ID.
   - Free tier: 50 submissions/month, forwards each one to your inbox.

2. **GitHub Pages**
   - Push this repo to GitHub as a **public** repo (Pages on a private repo needs GitHub Pro).
   - Repo → **Settings → Pages → Build and deployment → Source: Deploy from a branch → `main` / `/ (root)`** → Save.
   - Site goes live at `https://<username>.github.io/<repo-name>/` within a minute or two.

## Editing

Edit `index.html`, commit, push. Pages redeploys automatically.

## Files

- `index.html` — the whole site (CSS and JS inline)
- `logo.svg` — the gate mark, white ink for dark backgrounds
- `.nojekyll` — tells Pages to serve files as-is
