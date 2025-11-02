# Portfolio

This repository contains the static portfolio website for Anubhav Singh.

Purpose
- Host this site using GitHub Pages (branch `main`, root folder).

Quick start
1. Open PowerShell and go to the project folder:

```powershell
cd 'C:\Users\dell\OneDrive\Desktop\anubhavportfolio\new portfolio'
```

2. (Optional) Rename any files with spaces (example already applied in `index.html`):

```powershell
# example (adjust if needed)
Rename-Item 'formal picture .jpg' 'formal-picture.jpg' -ErrorAction SilentlyContinue
```

3. Initialize git, commit, and push to GitHub (replace `USERNAME` with your GitHub username):

```powershell
git init
git add .
git commit -m "Prepare site for GitHub Pages"
git branch -M main
git remote add origin https://github.com/USERNAME/Portfolio.git
git push -u origin main
```

4. Enable GitHub Pages:
- Go to `https://github.com/USERNAME/Portfolio`
- Settings → Pages → Source: `main` branch, folder `/` (root)
- Save; the published URL will appear on that page (usually `https://USERNAME.github.io/Portfolio`).

Notes and tips
- Filenames on GitHub Pages are case-sensitive and spaces in filenames will be URL-encoded; prefer lowercase, dash-separated names (e.g., `formal-picture.jpg`).
- If you want a root user site (https://USERNAME.github.io), name the repository `USERNAME.github.io` instead of `Portfolio`.
- To use the commit message template provided here, run:

```powershell
git config --local commit.template COMMIT_TEMPLATE.md
```

If you want me to push the repo and enable Pages for you, I can guide you through the steps or help debug any errors you get when running the commands above.
