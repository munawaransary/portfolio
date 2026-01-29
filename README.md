# Personal Portfolio Website

[![Netlify Status](https://api.netlify.com/api/v1/badges/your-badge-id/deploy-status)](https://app.netlify.com/sites/your-site/deploys)

My personal portfolio website built with Gatsby and deployed on GitHub Pages.

![Demo](./src/images/demo.png)

## 🚀 Quick Start

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn

### Installation & Setup

1. Clone the repository
```bash
git clone https://github.com/munawaransary/portfolio_moon_e_war.git
cd portfolio_moon_e_war
```

2. Install dependencies
```bash
npm install
```

3. Start the development server
```bash
npm start
```

The site will be running at `http://localhost:8000`

## 🛠️ Building and Running for Production

1. Generate a full static production build
```bash
npm run build
```

2. Preview the site as it will appear once deployed
```bash
npm run serve
```

## 🚀 Deploying to GitHub Pages

1. Update the repository URL in `package.json` and `gatsby-config.js` if needed

2. Deploy to GitHub Pages
```bash
npm run deploy
```

This will build the site and push it to the `gh-pages` branch.

3. Enable GitHub Pages in your repository settings:
   - Go to Settings > Pages
   - Source: Deploy from a branch
   - Branch: `gh-pages` / `root`
   - Save

Your site will be live at: `https://munawaransary.github.io/portfolio_moon_e_war/`

## 📝 Customization

### Personal Information

Update the following files with your information:

- `src/config.js` - Email, social media links, navigation
- `src/components/sections/hero.js` - Hero section content
- `src/components/sections/about.js` - About section and skills
- `content/jobs/` - Work experience
- `content/featured/` - Featured projects
- `content/projects/` - Other projects
- `static/resume.pdf` - Your resume

### Colors

The color scheme can be customized in `src/config.js`:

```javascript
colors: {
  green: '#64ffda',
  navy: '#0a192f',
  darkNavy: '#020c1b',
}
```

## 🎨 Tech Stack

- **Framework:** [Gatsby](https://www.gatsbyjs.com/)
- **Styling:** [Styled Components](https://styled-components.com/)
- **Animations:** [anime.js](https://animejs.com/), [ScrollReveal](https://scrollrevealjs.org/)
- **Deployment:** GitHub Pages

## 📦 Project Structure

```
portfolio_moon_e_war/
├── content/
│   ├── featured/          # Featured projects
│   ├── jobs/              # Work experience
│   └── projects/          # Other projects
├── src/
│   ├── components/        # React components
│   ├── images/            # Images and icons
│   ├── pages/             # Page components
│   ├── styles/            # Global styles
│   └── config.js          # Site configuration
├── static/                # Static files (resume, etc.)
├── gatsby-config.js       # Gatsby configuration
└── package.json           # Dependencies and scripts
```

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

Design inspired by [Brittany Chiang's portfolio](https://brittanychiang.com/)

---

Built with ❤️ by Munawar Mahtab Ansary
