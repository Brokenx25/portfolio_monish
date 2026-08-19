# Portfolio — Monish Naresh Kumar

Self-contained `index.html` (dark/light, responsive, cursor-reactive) + CV & résumé PDFs.
No build step; fonts load from a CDN. Keep the PDFs beside `index.html`.

---

## Deploy in its own repository (GitHub Pages)

1. Create a repo named **`portfolio`** on your account (`Brokenx25`).
2. Push this folder:
   ```bash
   cd portfolio
   git init && git add . && git commit -m "Portfolio site"
   git branch -M main
   # with GitHub CLI:
   gh repo create portfolio --public --source=. --push
   #  …or without gh, after creating the empty repo on github.com:
   # git remote add origin https://github.com/Brokenx25/portfolio.git
   # git push -u origin main
   ```
3. On the repo → **Settings → Pages → Source: Deploy from a branch → `main` / `root` → Save.**
4. Live in ~1 minute at **https://brokenx25.github.io/portfolio**

## Alternative — Netlify (no Git)
app.netlify.com → **Add new site → Deploy manually** → drag this `portfolio` folder in.
