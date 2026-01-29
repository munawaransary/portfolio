# Deployment Guide for GitHub Pages

## Step-by-Step Instructions

### 1. Install Dependencies

First, install all the required packages:

```bash
npm install
```

### 2. Test Locally

Before deploying, make sure everything works locally:

```bash
npm start
```

Visit `http://localhost:8000` to see your portfolio. Press `Ctrl+C` to stop the server.

### 3. Create GitHub Repository

1. Go to [GitHub](https://github.com) and create a new repository
2. Name it: `portfolio_moon_e_war` (or any name you prefer)
3. **Do NOT** initialize with README, .gitignore, or license (we already have these)
4. Click "Create repository"

### 4. Connect Local Repository to GitHub

```bash
# Add all files to git
git add .

# Commit the files
git commit -m "Initial commit: Personal portfolio website"

# Add your GitHub repository as remote (replace with your actual GitHub username)
git remote add origin https://github.com/munawaransary/portfolio_moon_e_war.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### 5. Deploy to GitHub Pages

Run the deployment command:

```bash
npm run deploy
```

This command will:
- Build your site for production
- Create a `gh-pages` branch
- Push the built files to that branch

### 6. Enable GitHub Pages

1. Go to your repository on GitHub
2. Click on **Settings** (top right)
3. Scroll down to **Pages** (left sidebar)
4. Under **Source**, select:
   - Branch: `gh-pages`
   - Folder: `/ (root)`
5. Click **Save**

### 7. Access Your Live Site

After a few minutes, your site will be live at:

```
https://munawaransary.github.io/portfolio_moon_e_war/
```

## Updating Your Portfolio

Whenever you make changes:

```bash
# Make your changes to the files
# Then:

git add .
git commit -m "Description of your changes"
git push origin main

# Deploy the updated version
npm run deploy
```

## Troubleshooting

### Issue: Site shows 404 or blank page

**Solution:** Make sure the `pathPrefix` in `gatsby-config.js` matches your repository name:

```javascript
pathPrefix: '/portfolio_moon_e_war',
```

### Issue: npm install fails

**Solution:** Make sure you have Node.js v14 or higher installed:

```bash
node --version
```

If you need to update Node.js, use [nvm](https://github.com/nvm-sh/nvm):

```bash
nvm install 14
nvm use 14
```

### Issue: Images not loading

**Solution:** 
1. Make sure images are in the correct folders (`src/images/`, `content/featured/`, etc.)
2. Rebuild the site: `npm run clean && npm run build`

### Issue: Deploy command fails

**Solution:**
1. Make sure you've committed all changes first
2. Check that gh-pages package is installed: `npm install gh-pages --save-dev`
3. Try running: `npm run clean` then `npm run deploy`

## Custom Domain (Optional)

If you want to use a custom domain like `munawar.dev`:

1. Buy a domain from a registrar (Namecheap, GoDaddy, etc.)
2. Add a file named `CNAME` to the `static/` folder with your domain:
   ```
   munawar.dev
   ```
3. In your domain registrar's DNS settings, add:
   - Type: `A` Record
   - Host: `@`
   - Value: `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
   
4. Also add:
   - Type: `CNAME` Record
   - Host: `www`
   - Value: `munawaransary.github.io`

5. Redeploy: `npm run deploy`
6. In GitHub Settings > Pages, enter your custom domain and save

## Need Help?

- [Gatsby Documentation](https://www.gatsbyjs.com/docs/)
- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- Check the [Issues](https://github.com/munawaransary/portfolio_moon_e_war/issues) page

---

Good luck with your portfolio! 🚀
