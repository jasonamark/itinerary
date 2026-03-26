# Japan family trip itinerary (static site)

This folder is set up for **[GitHub Pages](https://pages.github.com/)**: the site entry file is **`index.html`**. Local images live under **`assets/venues/`**.

## Deploy with GitHub Pages

1. Create a new repository on GitHub (empty repo is fine), e.g. `japan-trip-itinerary`.

2. From this folder on your machine:

   ```bash
   cd ~/Documents/JAS/itinerary
   git init
   git add index.html assets README.md .gitignore
   git commit -m "Add itinerary site for GitHub Pages"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git
   git push -u origin main
   ```

3. On GitHub: **Settings → Pages** → **Build and deployment**

   - **Source**: Deploy from a branch  
   - **Branch**: `main`  
   - **Folder**: `/ (root)`

4. After a minute or two, open:

   `https://YOUR_USERNAME.github.io/YOUR_REPO/`

   Maps iframes and local images need that `https://` URL (not `file://`).

## Optional: custom domain

If you buy a domain later: **Settings → Pages → Custom domain**, then add the DNS records GitHub shows (usually `A` / `CNAME`).
