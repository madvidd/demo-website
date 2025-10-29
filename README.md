# Donya Ghahremani — Minimal Portfolio (Light Pastel Blue)

A clean, single‑page website for a pyrography (wood burning) artist. Built with vanilla HTML/CSS/JS — perfect for GitHub Pages.

## Preview

Open `index.html` locally, or push this folder to GitHub and enable **Pages**.

## Customize

- **Text:** Edit copy directly in `index.html` (About, Highlights, Contact email).
- **Gallery:** Replace SVGs in `/assets` with your own images **using the same filenames** (e.g., `gallery-1.svg` → `gallery-1.jpg`). The layout will adapt automatically.
- **Featured video:** In `index.html`, replace the YouTube `iframe` `src` with your preferred video ID.
- **Colors:** Adjust CSS variables in the `<style>` block at the top of `index.html` (e.g., `--bg`, `--accent`).

## Publish to GitHub Pages

1. Create a new **public** repository on GitHub (e.g., `donya-site`).
2. Upload the files in this folder, or push via Git:
   ```bash
   git init
   git add .
   git commit -m "Initial site"
   git branch -M main
   git remote add origin https://github.com/<your-user>/<your-repo>.git
   git push -u origin main
   ```
3. In the repo, go to **Settings → Pages**:
   - **Source:** `Deploy from a branch`
   - **Branch:** `main` / `/ (root)`
4. Wait a minute, then visit the URL shown in Pages settings (e.g., `https://<your-user>.github.io/<your-repo>/`).

### Optional: Custom Domain
- Add your domain in **Pages → Custom domain** (e.g., `donyaghahremani.com`).
- Create a `CNAME` file with your domain.
- Point DNS to GitHub Pages (docs: https://docs.github.com/pages).

## Credits & Links
- Instagram: https://www.instagram.com/pyrographydonya
- YouTube: https://www.youtube.com/@donyaghahremani

## License
MIT — feel free to reuse this template.
