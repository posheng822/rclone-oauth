# Personal rclone Google Drive OAuth information site

This repository contains **public informational content** for a personal rclone Google Drive OAuth client. It does not contain OAuth credentials or any Drive files.

## Pages
- `index.html`: purpose, features, and scope.
- `privacy.html`: privacy policy covering Drive API data access and local token storage.
- `terms.html`: usage description.

## Deployment
With **GitHub Free**, GitHub Pages requires a **public** repository.

1. After confirming files contain no confidential information, set the repository to Public under Settings → General → Danger Zone → Change repository visibility.
2. Go to Settings → Pages → Build and deployment → Deploy from a branch → `main` → `/(root)` → Save.
3. Verify the public URLs:
   - https://posheng822.github.io/rclone-oauth/
   - https://posheng822.github.io/rclone-oauth/privacy.html
   - https://posheng822.github.io/rclone-oauth/terms.html
4. In Google Auth Platform → Branding, set homepage/privacy policy/terms URLs, add the authorized domain `posheng822.github.io` if accepted, and complete any Search Console verification Google requires.
5. In Audience, select Publish app when Google permits it.

**Never upload** OAuth client secrets, tokens, `rclone.conf`, private files or Drive backups.

Operated independently for personal use. Not affiliated with Google or the rclone project.
