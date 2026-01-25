# BG Site (GitHub Pages)

This folder is ready to upload to **GitHub Pages** (free hosting).

## 1) Create the GitHub repo
Option A (project site)
- Create a new repo named `bg-site` (or any name)
- Upload these files

Option B (main GitHub Pages site)
- Create a repo named `<YOUR_GITHUB_USERNAME>.github.io`
- Upload these files

## 2) Turn on GitHub Pages
Repo → Settings → Pages
- Source: Deploy from a branch
- Branch: main (or master), folder: / (root)
- Save

GitHub will show your site URL once it publishes.

## 3) Make the contact form work (free)
Netlify Forms only works on Netlify. For GitHub Pages, use a form handler.

### Formspree (free tier)
1. Create a Formspree account
2. Create a new form and copy the endpoint (looks like `https://formspree.io/f/abcdwxyz`)
3. In `index.html`, replace:
   `https://formspree.io/f/REPLACE_ME`
   with your real endpoint.

Submissions will email you.

## 4) Next (optional)
- Replace the placeholder photos with your real work photos.
- Add a custom domain later (optional).
