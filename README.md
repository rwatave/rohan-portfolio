# Rohan Watave · Data Analytics Portfolio

A fast, single-file portfolio built with plain **HTML + CSS** — ideal for GitHub Pages.

## ✨ What's inside
- About, Skills, Experience, Education sections
- Project cards for:
  - Buttercup Games (SRE Golden Signals in Splunk)
  - Mortgage Servicing KPIs (Sutherland)
  - Retail Lending Analytics (HDFC)
  - Fraud Analytics Mini-Study
  - SQL Portfolio & Tableau Gallery
- Easy to edit text + placeholder links (GitHub, LinkedIn, Email, Resume)

## 🛠 Tech
- HTML5, CSS (no build, no frameworks)
- Works out-of-the-box on GitHub Pages

## 🚀 Quick start
1. Click **index.html** and update:
   - Your email, GitHub, LinkedIn URLs
   - Resume PDF link (put the PDF in the repo and update the `href` for “Download Résumé (PDF)”)
   - Project links (demo / repos / Tableau Public)
2. (Optional) Rename the repo to **`<your-username>.github.io`** to make this your user site.

## 📤 Publish to GitHub Pages
**Method A — From the web UI:**
1. Create a new repo on GitHub (e.g., `rohan-portfolio`), make it **Public**.
2. Upload the files in this folder (`Add file` → `Upload files` → commit).
3. Go to **Settings → Pages** → *Build and deployment* → Source: **Deploy from a branch**.
4. Select **Branch = main** and **Folder = /root**, click **Save**.
5. In ~1–2 minutes your site will be live at:
   - `https://<your-username>.github.io/rohan-portfolio/`
   - Or `https://<your-username>.github.io/` if the repo name is `<your-username>.github.io`.

**Method B — From your Mac (Terminal):**
```bash
# 1) In Terminal, go to the folder that contains these files
cd /path/to/rohan-portfolio

# 2) Initialize git and commit
git init
git add .
git commit -m "Add portfolio: index.html + README"

# 3) Create an empty repo on GitHub (using the website) and copy its HTTPS URL
#    Example: https://github.com/<your-username>/rohan-portfolio.git

# 4) Set remote and push
git branch -M main
git remote add origin https://github.com/<your-username>/rohan-portfolio.git
git push -u origin main
```

Then enable Pages: **Settings → Pages → Deploy from a branch → main /root**.

## 🧰 Editing tips
- Edit text directly in `index.html` (any editor). Commit and push to update your site.
- To add screenshots, create a folder `assets/` and link images: `<img src="assets/kpi.png" alt="KPI dashboard" />`.
- Keep project blurbs short: *problem → approach → result* (one paragraph + 2–3 bullets).

## 📄 License
MIT © 2025 Rohan Watave
