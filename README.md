# Varsha Kuchana — Data Analyst Portfolio

Professional portfolio website for data analyst roles.

**Live site (after deploy):** `https://varshakuchana.github.io/data-analyst-portfolio/`

## What's included

- Hero with resume download
- About, Skills, Projects (with Tableau embed)
- Experience, Education, Contact
- SEO & LinkedIn preview tags

## Deploy to GitHub Pages

### Step 1 — Create the repo on GitHub

1. Go to [github.com/new](https://github.com/new)
2. Repository name: `data-analyst-portfolio`
3. Set to **Public**
4. Do **not** add README, .gitignore, or license (we already have files)
5. Click **Create repository**

### Step 2 — Push your code

Run these commands in Terminal (replace with your path if needed):

```bash
cd "/Users/varshakuchana/Desktop/DATA ANALYST PORTFOLIO"

git init
git add .
git commit -m "Initial portfolio site for data analyst role"
git branch -M main
git remote add origin https://github.com/varshakuchana/data-analyst-portfolio.git
git push -u origin main
```

### Step 3 — Enable GitHub Pages

1. Open your repo on GitHub → **Settings** → **Pages**
2. Under **Build and deployment**, set Source to **Deploy from a branch**
3. Branch: `main` → Folder: `/ (root)` → **Save**
4. Wait 1–2 minutes. Your site will be live at:
   `https://varshakuchana.github.io/data-analyst-portfolio/`

### Step 4 — Add the URL to your resume & LinkedIn

Put the live link in:
- Resume header
- LinkedIn **Featured** section
- LinkedIn **Contact info** → Website

## Local preview

```bash
open index.html
```

## Files

| File | Purpose |
|------|---------|
| `index.html` | Page content |
| `styles.css` | Styling |
| `script.js` | Navigation & animations |
| `Varsha_Kuchana_Resume.pdf` | Downloadable resume |
