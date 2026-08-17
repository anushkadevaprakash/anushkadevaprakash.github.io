# anushka.sys

A personal site built like a Windows 98 desktop floating in a pink sky. Hand-coded, single file, no build step, no trackers.

## Deploy on GitHub Pages

1. Make a new repo (for example `anushka-site`, or `yourusername.github.io` for the root URL).
2. Add `index.html` to the repo root and push.
3. Go to **Settings, Pages, Build and deployment, Source: Deploy from a branch**, pick `main` / `root`, save.
4. Live in about a minute at `https://yourusername.github.io/anushka-site/`.

## Custom domain (later)

1. Add a `CNAME` file (no extension) to the repo containing just your domain.
2. At your DNS host: `A` records for the apex pointing to GitHub Pages IPs (`185.199.108.153`, `.109.153`, `.110.153`, `.111.153`), and a `CNAME` for `www` pointing to `yourusername.github.io`.
3. Settings, Pages, Custom domain, then enable **Enforce HTTPS**.

## What's wired up

Live social links (open in a new tab): X, GitHub, LinkedIn. Hot-pink text selection. Everything lives in `index.html`.
