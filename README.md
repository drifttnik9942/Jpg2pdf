# Images (JPEG/PNG/WebP) to PDF (PWA)

1. Create a new GitHub repo and upload all files in this folder to the root.
2. Repo Settings > Pages > Deploy from a branch > `main` / `(root)` > Save.
3. Open `https://<your-username>.github.io/<repo-name>/` on your iPhone in Safari.
4. Share button > Add to Home Screen. It then works offline.

When you change files, bump `CACHE` in sw.js (e.g. jpeg2pdf-v3) so phones pick up the update.
