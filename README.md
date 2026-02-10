# Valentines

A simple HTML site for GitHub Pages.

## Deploy to a public link (GitHub Pages)

1. **Create a GitHub repository**
   - Go to [github.com/new](https://github.com/new)
   - Name it (e.g. `valentines` or `Valentines`)
   - Choose **Public**, leave "Add a README" unchecked if this folder already has files
   - Click **Create repository**

2. **Push this folder to the repo** (from your project folder in Terminal):

   ```bash
   cd /Users/bhargavsriram/Valentines
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
   git push -u origin main
   ```
   Replace `YOUR_USERNAME` and `YOUR_REPO_NAME` with your GitHub username and repo name.

3. **Turn on GitHub Pages**
   - In the repo: **Settings** → **Pages** (left sidebar)
   - Under **Source**: choose **Deploy from a branch**
   - **Branch**: `main` (or `master`)
   - **Folder**: `/ (root)`
   - Click **Save**

4. **Your public link**
   - After 1–2 minutes, the site will be at:
   - **`https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/`**

Replace `index.html` with your own HTML (or add more `.html` files and link to them). Every push to `main` will update the live site.
