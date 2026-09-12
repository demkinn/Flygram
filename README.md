# Flygram 🪰

GitHub-ready Flygram website.

## Deploy to GitHub Pages

1. Create a new GitHub repository named `flygram`.
2. Upload all files from this folder to the repository.
3. Make sure the default branch is `main`.
4. Open **Settings → Pages** and set **Source** to **GitHub Actions**.
5. Push/commit the files. The workflow will build and publish the site.
6. Your URL will be:
   `https://YOUR-GITHUB-USERNAME.github.io/flygram/`

The Vite `base` is already configured for a repository named `flygram`.
If you choose another repository name, change `base` in `vite.config.ts` to `/<repo-name>/`.
