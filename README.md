# Satlabs Redesign

This repository contains a static landing page (index.html) for Satlabs, ready to be deployed to Vercel.

What I added
- index.html — the full HTML you provided, placed at the repository root so Vercel serves it as the site root.
- satlabs-redesign.html — a copy preserved for reference.
- vercel.json — minimal rewrite so clean URLs fall back to index.html.

Deploying to Vercel
1. Go to https://vercel.com and import the project from your GitHub account (sanskar112/satlabs-redesign).
2. Vercel should detect a static project. No build step is required.
3. If you already have the project connected, trigger a redeploy from the Vercel dashboard or push a new commit.

If you still see a 404 after this change
- Make sure the Vercel project is pointed at the `main` branch.
- Confirm the build & output settings; for a static site set Framework Preset to "Other" and leave Build Command blank.
- Check that there are no custom routes in Vercel overriding the root path.

If you want, I can add a GitHub Action to automatically trigger a Vercel deploy via Vercel CLI — tell me and I’ll add it.
