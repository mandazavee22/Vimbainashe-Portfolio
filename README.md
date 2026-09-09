# Vimbainashe Mandaza — Portfolio

A single-file HTML/CSS/JS portfolio site. All content is driven by the `CONFIG` object near the bottom of `index.html` — edit that object to update projects, skills, experience, etc. without touching any markup.

## Structure
```
portfolio/
├── index.html          # the whole site (HTML + CSS + JS in one file)
└── assets/
    ├── certificate-degree.jpg
    ├── certificate-alevel.jpg
    ├── certificate-olevel.jpg
    └── Vimbainashe-Mandaza-CV.pdf
```

## Run locally
Open `index.html` directly in a browser, or serve it (recommended, avoids some browser file:// restrictions):
```bash
python -m http.server 8000
```
Then visit `http://localhost:8000`.

## Deploy on GitHub Pages
1. Push this folder to a GitHub repo (see commands below).
2. On GitHub: **Settings → Pages → Source** → select the `main` branch and `/ (root)` folder → **Save**.
3. Your site goes live at `https://<your-username>.github.io/<repo-name>/` within a minute or two.

## Push to GitHub
```bash
cd portfolio
git init
git add .
git commit -m "Initial portfolio commit"
git branch -M main
git remote add origin https://github.com/<your-username>/<repo-name>.git
git push -u origin main
```
