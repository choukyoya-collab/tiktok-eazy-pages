# TikTok Eazy - GitHub Pages site

This archive contains the static site ready to be deployed on GitHub Pages.

Structure:

- index.html (main web app)
- privacy/index.html
- terms/index.html
- _redirects (Netlify-style redirects used by some static hosts)
- verification TXT files in root for TikTok site verification

To deploy:
1. Create a repository `tiktok-eazy-pages` on GitHub.
2. Upload all files in this archive to the repository root (do NOT keep an extra nested folder).
3. In the repo Settings → Pages set the source branch to `main` and folder as `/ (root)`.
4. Wait a minute, then open the verification URL:
   `https://<your-username>.github.io/tiktok-eazy-pages/<verification-file>.txt`

Replace `<your-username>` with your GitHub username.
