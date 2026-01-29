# ✅ TODO Before Deploying

## Critical (Must Do)

- [ ] **Install dependencies**: Run `npm install`
- [ ] **Test locally**: Run `npm start` and check everything works at `http://localhost:8000`
- [ ] **Create GitHub repository** named `portfolio_moon_e_war`
- [ ] **Update GitHub username** in the following files if different from `munawaransary`:
  - [ ] `package.json` - Line 7: repository URL
  - [ ] `gatsby-config.js` - Line 8: siteUrl
  - [ ] `README.md` - Update all GitHub links

## Highly Recommended

- [ ] **Replace profile picture**: `src/images/me.jpg` with your actual photo
- [ ] **Replace logo**: `src/images/logo.png` with your personal logo/icon
- [ ] **Add project screenshots**: Replace `demo.png` in `content/featured/` folders with actual project images
- [ ] **Add GitHub links**: Update `github:` field in project markdown files with actual repository URLs
- [ ] **Verify resume**: Check that `static/resume.pdf` is your latest CV

## Optional (Nice to Have)

- [ ] **Update colors**: Customize colors in `src/config.js` if you want a different theme
- [ ] **Add more social links**: Add Twitter, Instagram, etc. in `src/config.js`
- [ ] **Update Google Analytics**: Add your tracking ID in `gatsby-config.js` (or remove the plugin)
- [ ] **Add external project links**: Update `external:` field in project files with live demo URLs
- [ ] **Customize favicon**: Replace files in `src/images/favicons/` folder

## Verification Checklist

Before running `npm run deploy`, verify:

- [ ] All personal information is correct (name, email, links)
- [ ] No placeholder text remains (search for "Brittany" to be sure)
- [ ] All links work (GitHub, LinkedIn, email)
- [ ] Images load properly
- [ ] Resume PDF opens correctly
- [ ] Site looks good on mobile (use browser dev tools)

## Deployment Steps

Once everything above is done:

```bash
# 1. Add and commit all files
git add .
git commit -m "Initial commit: Personal portfolio"

# 2. Connect to GitHub (replace with your username)
git remote add origin https://github.com/munawaransary/portfolio_moon_e_war.git
git branch -M main
git push -u origin main

# 3. Deploy to GitHub Pages
npm run deploy

# 4. Enable GitHub Pages in repository settings
# Settings → Pages → Source: gh-pages branch
```

## After Deployment

- [ ] Wait 2-3 minutes for GitHub Pages to build
- [ ] Visit your site: `https://YOUR_USERNAME.github.io/portfolio_moon_e_war/`
- [ ] Test all links and navigation
- [ ] Check on mobile device
- [ ] Share with friends for feedback!

## Need Help?

- Read `QUICK_START.md` for simplified instructions
- Read `DEPLOYMENT_GUIDE.md` for detailed step-by-step guide
- Read `CUSTOMIZATION_SUMMARY.md` to see what's been customized
- Check the [Gatsby documentation](https://www.gatsbyjs.com/docs/)

---

Good luck! Your portfolio is almost ready to go live! 🚀
