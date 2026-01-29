# Portfolio Customization Summary

## ✅ What Has Been Customized

### Personal Information

**File: `src/config.js`**
- Email: munawarmahtabansary@gmail.com
- GitHub: https://github.com/munawaransary
- LinkedIn: https://linkedin.com/in/munawar-mahtab-ansary

**File: `gatsby-config.js`**
- Site title: Munawar Mahtab Ansary
- Description: Machine Learning Engineer specializing in NLP, AI systems, and full-stack development
- Site URL: https://munawaransary.github.io/portfolio_moon_e_war

### Hero Section

**File: `src/components/sections/hero.js`**
- Name: Munawar Mahtab Ansary
- Tagline: "I build intelligent AI systems"
- Description: Machine Learning Engineer at Innospace Infotech Ltd.
- Focus areas: RAG, computer vision, conversational AI

### About Section

**File: `src/components/sections/about.js`**
- Personal story about ML journey at BRAC University
- Work experience at Innospace, DataSoft, and BRAC University
- Thesis project: BanglaMUX
- Skills: Python, PyTorch, TensorFlow, Django, Laravel, RAG, NLP, AWS, MySQL, Git

### Work Experience

**Folder: `content/jobs/`**

1. **Innospace Infotech Ltd.** (September 2025 - Present)
   - Junior Machine Learning Engineer
   - Projects: Innovert, Question Formatting Pipeline, RAG Chatbot, QA System

2. **DataSoft** (February 2025 - June 2025)
   - Intern
   - Projects: Microfin360, Microfin Chatbot

3. **BRAC University** (June 2024 - May 2025)
   - Student Tutor/TA
   - Graded assignments, provided consultation, conducted review classes

### Featured Projects

**Folder: `content/featured/`**

1. **BanglaMUX** - Regional dialect detection & translation
   - Tech: Python, Transformer Models, Whisper, BERT, Bangla T5, NLP

2. **QuickTrips** - Car rental platform
   - Tech: Django, HTML, CSS, Chatbase, REST APIs

3. **Sexism Detection with BiLSTM**
   - Tech: Python, Deep Learning, BiLSTM, NLP, GloVe, TensorFlow

### Other Projects

**Folder: `content/projects/`**

1. Flight Management System
2. Airborne Autos - Obstacle-Jumping Car Game
3. Innovert - Font to Unicode Converter
4. Full Question Formatting Pipeline
5. Microfin Department Chatbot

### Static Files

- **Resume**: `static/resume.pdf` - Your CV has been added

## 📝 Files You May Want to Update

### Images

1. **Profile Picture**: `src/images/me.jpg`
   - Replace with your photo
   - Recommended size: 500x500px

2. **Logo**: `src/images/logo.png`
   - Replace with your personal logo/icon
   - Recommended size: 96x96px

3. **Project Screenshots**: `content/featured/*/demo.png`
   - Add actual screenshots of your projects
   - Recommended size: 1200x800px

### Optional Customizations

1. **Colors** (`src/config.js`):
   ```javascript
   colors: {
     green: '#64ffda',    // Accent color
     navy: '#0a192f',     // Background
     darkNavy: '#020c1b', // Darker background
   }
   ```

2. **Google Analytics** (`gatsby-config.js`):
   - Line 155: Replace with your tracking ID
   - Or remove the plugin if you don't want analytics

3. **Social Media Links** (`src/config.js`):
   - Add Twitter, Instagram, etc. if you want

## 🔗 GitHub Links to Update

If you add your projects to GitHub, update these files with the actual repository URLs:

- `content/featured/BanglaMUX/index.md` - Add `github: 'https://github.com/...'`
- `content/featured/QuickTrips/index.md` - Add `github: 'https://github.com/...'`
- `content/featured/SexismDetection/index.md` - Add `github: 'https://github.com/...'`
- All files in `content/projects/` - Add `github:` field

## 📊 Education Section

The template doesn't have a dedicated education section, but you can add one by:

1. Creating `src/components/sections/education.js`
2. Adding it to `src/pages/index.js`
3. Or mentioning it in the About section (already done)

Your education:
- BRAC University - B.Sc. Computer Science, CGPA: 3.91 (Sept 2021 - May 2025)
- Notre Dame College - HSC, GPA: 5.00 (July 2018 - March 2020)

## 🏆 Achievements

Consider adding a section for your achievements:
- 50% merit scholarship at BRAC University
- 11th place in programming contest (Team Rocket)
- VC's List (6 semesters)
- Dean's List (1 semester)
- Vitalizers 2.0 Business Case Competition semi-finalist

## 📜 Certifications

You may want to add a certifications section with:
- The Complete Python Bootcamp (Udemy)
- Cleaning Data in Python (Datacamp)
- Feature Engineering for Machine Learning (Datacamp)
- Machine Learning with Tree-Based Models (Datacamp)

## 🎯 Next Steps

1. Replace placeholder images with actual photos/screenshots
2. Add GitHub repository links to your projects
3. Test the site locally: `npm start`
4. Deploy to GitHub Pages: `npm run deploy`
5. Share your portfolio link!

---

Your portfolio is ready to go live! 🚀
