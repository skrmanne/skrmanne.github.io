# Sai Kumar Reddy Manne — Portfolio

A clean, static academic portfolio website inspired by [Jon Barron's site](https://jonbarron.info/).

## Hosting on GitHub Pages (Free)

1. Create a new GitHub repository (e.g., `saikrmanne.github.io` for a user site, or any name for a project site).
2. Push this folder's contents to the `main` branch:
   ```bash
   cd website
   git init
   git add .
   git commit -m "Initial portfolio site"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<repo-name>.git
   git push -u origin main
   ```
3. Go to **Settings → Pages** in your GitHub repo.
4. Under **Source**, select `main` branch and `/ (root)` folder, then click **Save**.
5. Your site will be live at `https://<your-username>.github.io/<repo-name>/` (or `https://<your-username>.github.io/` if repo is named `<username>.github.io`).

## Customization

- **Profile photo**: Replace `profile.png` with your own photo.
- **Content**: Edit `index.html` directly — it's a single self-contained file with inline CSS.
- **No build step required** — just edit and push.

## Stack

- Pure HTML + CSS (no JavaScript, no frameworks, no build tools)
- Google Fonts (Lato)
- Font Awesome icons (loaded via CDN)
