# Arjun Bharadwaj Raveendran — Portfolio

Single-file interactive portfolio. Vanilla HTML/CSS/JS, zero dependencies, no build step.

**Interactive features:** particle constellation hero, typewriter roles, tabbed experience, 3D-tilt project cards, a live fraud-scoring demo, a playable Flappy Bird, a terminal easter egg (press `` ` `` or click `>_ terminal`), and the Konami code (↑↑↓↓←→←→BA).

## Files

- `index.html` — the entire site
- `Arjun_Bharadwaj_Raveendran_Resume.pdf` — served by the "Download résumé" buttons

## Preview locally

Just double-click `index.html`, or:

```bash
python -m http.server 8000
# open http://localhost:8000
```

## Deploy to GitHub Pages (recommended: user site)

Your site will live at **https://1arjunraveendran.github.io**

1. Create a new repo on GitHub named exactly: `1arjunraveendran.github.io` (public, no README)
2. From this folder, run:

```bash
git init
git add .
git commit -m "Launch portfolio"
git branch -M main
git remote add origin https://github.com/1arjunraveendran/1arjunraveendran.github.io.git
git push -u origin main
```

3. Wait ~1 minute. Done — visit https://1arjunraveendran.github.io

GitHub Pages auto-deploys user sites from `main`; no settings needed.

## Alternative: project site

If you'd rather keep `1arjunraveendran.github.io` for something else, name the repo anything (e.g. `portfolio`), push the same way, then on GitHub: **Settings → Pages → Source: Deploy from a branch → main / (root) → Save**. Site appears at `https://1arjunraveendran.github.io/portfolio/`.

## Updating later

Edit `index.html`, then:

```bash
git add . && git commit -m "Update" && git push
```

Changes go live in about a minute.

## Custom domain (optional)

Buy a domain, add a `CNAME` file containing the domain to this repo, and point the domain's DNS (CNAME record) at `1arjunraveendran.github.io`. Full guide: https://docs.github.com/pages
