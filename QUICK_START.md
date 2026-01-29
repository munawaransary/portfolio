# Quick Start Guide

## 🚀 Get Your Portfolio Live in 5 Minutes

### Step 1: Install Dependencies (2 minutes)

Open terminal in this folder and run:

```bash
npm install
```

Wait for it to complete. You'll see a lot of text - that's normal!

### Step 2: Test It Locally (1 minute)

```bash
npm start
```

Open your browser and go to: `http://localhost:8000`

You should see your portfolio! Press `Ctrl+C` in terminal to stop.

### Step 3: Create GitHub Repository (1 minute)

1. Go to https://github.com/new
2. Repository name: `portfolio_moon_e_war`
3. Keep it **Public**
4. **Don't** check any boxes
5. Click "Create repository"

### Step 4: Push to GitHub (30 seconds)

Copy these commands one by one (replace `munawaransary` with your GitHub username):

```bash
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/munawaransary/portfolio_moon_e_war.git
git branch -M main
git push -u origin main
```

### Step 5: Deploy (30 seconds)

```bash
npm run deploy
```

Wait for it to finish (you'll see "Published").

### Step 6: Enable GitHub Pages (30 seconds)

1. Go to your repository on GitHub
2. Click **Settings** → **Pages** (left sidebar)
3. Under Source, select: Branch `gh-pages`, Folder `/ (root)`
4. Click **Save**

### 🎉 Done!

Your site will be live in 2-3 minutes at:

```
https://YOUR_USERNAME.github.io/portfolio_moon_e_war/
```

Replace `YOUR_USERNAME` with your actual GitHub username.

---

## 📝 Making Changes Later

1. Edit the files you want to change
2. Run these commands:

```bash
git add .
git commit -m "Updated portfolio"
git push origin main
npm run deploy
```

Wait 2-3 minutes and your changes will be live!

---

## ⚠️ Common Issues

**"npm: command not found"**
- Install Node.js from: https://nodejs.org/

**"Permission denied" or "EACCES" error**
- Run: `sudo npm install -g npm@latest`

**Site shows blank page**
- Check that `pathPrefix` in `gatsby-config.js` matches your repo name

**Need more help?**
- Read the full `DEPLOYMENT_GUIDE.md`
- Or open an issue on GitHub

---

Good luck! 🚀
