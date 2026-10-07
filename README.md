# Meteor Client Website

Static HTML/CSS/JS recreation of the supplied Meteor Client website design.

## Put it on GitHub Pages

1. Extract this ZIP.
2. Upload `index.html`, `styles.css`, `script.js`, and the `assets` folder to the root of your GitHub repository.
3. Open **Settings → Pages** in the repository.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select your main branch and `/ (root)`, then save.
6. Wait for GitHub Pages to deploy.
7. Under **Settings → Pages → Custom domain**, enter your existing custom domain.
8. If GitHub asks for DNS changes, add the records it shows at your domain provider.
9. Enable HTTPS once it becomes available.

## Change your links

Open `index.html` and replace:
- `https://discord.com/` with your Discord invite
- `https://github.com/` with your GitHub repository
- `https://youtube.com/` with your YouTube channel
- `#` on the two download buttons with the actual download/release URLs
- `#login` with your login page if you have one

The site is completely static, so no server is required for GitHub Pages.
