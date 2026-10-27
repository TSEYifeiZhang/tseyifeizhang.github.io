# Yifei Zhang - Academic Homepage (`luost26/academic-homepage` Template)

This repository contains the complete, pre-populated Jekyll source code for **Prof. Yifei Zhang's** academic homepage, built using the [`luost26/academic-homepage`](https://github.com/luost26/academic-homepage) template and pre-populated with your CV (`files/Yifei_Zhang.pdf`), publications, working papers, awards, teaching, and academic service.

## Quick Deployment to `tseyifeizhang.github.io`

### Option A: Using the Official Template on GitHub + Copying Your Data Files (Recommended for Upstream Updates)
1. Visit [`https://github.com/luost26/academic-homepage`](https://github.com/luost26/academic-homepage) and click **Use this template** -> **Create a new repository** (or fork it).
2. Copy the pre-populated folders from this archive into your repository:
   - `_config.yml`
   - `_data/profile.yml`, `_data/navigation.yml`, `_data/authors.yml`
   - `_publications/` (all 6 papers with abstracts, awards, and SSRN/journal links)
   - `_news/` (recent highlights)
   - `files/Yifei_Zhang.pdf` (your CV)
   - `assets/images/` (institution badges & paper cover visuals)
3. Push to your `tseyifeizhang.github.io` repository on the `main` branch and enable **GitHub Pages** under **Settings -> Pages**.

### Option B: Direct Push of This Complete Repository
1. Unzip this archive and initialize or push directly to your GitHub repository:
   ```bash
   git init
   git add .
   git commit -m "Migrate academic homepage to luost26/academic-homepage template"
   git branch -M main
   git remote add origin https://github.com/tseyifeizhang/tseyifeizhang.github.io.git
   git push -u origin main
   ```
2. To add your personal headshot photo, place your photo at `assets/images/photos/portrait.jpg` and update `portrait_url: /assets/images/photos/portrait.jpg` in `_data/profile.yml`.
