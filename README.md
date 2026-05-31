# Alireza Javadian Sabet — Academic Website

This is a minimal static academic website designed for GitHub Pages.

## Quick setup

1. Create a new GitHub repository named either:
   - `javadiansabet.com`, or
   - `alirezajsabet.github.io` if your GitHub username is `alirezajsabet`.

2. Upload these files to the repository:
   - `index.html`
   - `style.css`
   - `CNAME`
   - the `assets/` folder

3. Add your photo:
   - Put your photo inside the `assets/` folder.
   - Rename it exactly to `profile.jpg`.
   - If your file is PNG, either rename/update the HTML path to `assets/profile.png`, or convert it to JPG.

4. Enable GitHub Pages:
   - Go to repository `Settings`.
   - Go to `Pages`.
   - Under `Build and deployment`, choose `Deploy from a branch`.
   - Select branch: `main`.
   - Select folder: `/root`.
   - Save.

5. Custom domain:
   - In GitHub Pages settings, set the custom domain to:
     `javadiansabet.com`
   - Keep the `CNAME` file in the repository.

6. Cloudflare DNS records:
   - Add a CNAME record:
     - Name: `www`
     - Target: your GitHub Pages URL, e.g. `YOURUSERNAME.github.io`
   - For the root domain, use GitHub Pages A records or Cloudflare CNAME flattening.

GitHub Pages documentation for custom domains:
https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site
