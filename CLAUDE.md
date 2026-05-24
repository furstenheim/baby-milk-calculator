# Baby Milk Cooling Calculator

Single-page physics-based calculator showing how long to cool baby milk to a safe feeding temperature.

## Branch convention

**Always commit directly to `master`.** This repo has no feature branches — push every change straight to master. Do not create or use any other branch.

## Project structure

- `index.html` — the entire app (HTML + CSS + JS, no build step)
- `.github/workflows/deploy.yml` — deploys to GitHub Pages on every push to master

## Deployment

GitHub Pages is the host. To activate it: repository Settings → Pages → Source → **GitHub Actions**.  
Every push to master triggers the workflow and publishes automatically.

## Physics model

Newton's Law of Cooling through a composite cylindrical wall. See the in-page physics section of `index.html` for full details.
