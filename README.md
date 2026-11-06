# 🚀 Kunal Nirmalkar - Portfolio Website

A modern, animated portfolio website showcasing creative development and DevOps projects.

## 🌐 Live Demo
Your portfolio will be live at: `https://kunalnportfolio.netlify.app/`

---

## 📁 Files Included

```
portfolio/
├── index.html          # Main portfolio website
├── netlify.toml        # Netlify configuration
├── _redirects          # Routing configuration
├── resume.pdf          # Your resume (add this)
└── README.md           # This file
```

---

## 🎨 Features

### ✨ Design Features
- ✅ Custom animated cursor
- ✅ Smooth scroll with Lenis
- ✅ GSAP animations throughout
- ✅ Preloader animation
- ✅ Mobile-responsive design
- ✅ Minimalist dark theme
- ✅ Interactive project cards
- ✅ Full-screen navigation menu

### 🛠️ Technical Features
- ✅ Netlify Forms integration
- ✅ Contact form with validation
- ✅ Font Awesome icons
- ✅ Google Fonts (Space Grotesk & Syne)
- ✅ CSS Grid & Flexbox layout
- ✅ Modern CSS custom properties
- ✅ Scroll-triggered animations

---

## 📂 Your Projects Showcase

### 1️⃣ **CivicConnect India**
**Description:** A government-grade grievance redressal portal. Features real-time stats and a citizen leaderboard for "One Nation, One Platform."

**Tech Stack:**
- TypeScript
- MERN Stack (MongoDB, Express, React, Node.js)
- DevOps

**Links:**
- 🔗 Live: https://jantaseva.netlify.app/
- 💻 Code: https://github.com/KunalNirmalkar07/CivicvConnect-India

---

### 2️⃣ **Discover Chhattisgarh**
**Description:** A high-performance cultural explorer with interactive guides for the heritage and natural wonders of Chhattisgarh.

**Tech Stack:**
- TypeScript
- React
- Tailwind CSS

**Links:**
- 🔗 Live: https://discoverchhattisgarh.netlify.app/
- 💻 Code: https://github.com/KunalNirmalkar07/Discover-Chhattisgarh

---

### 3️⃣ **Nayi-Raah**
**Description:** An educational platform designed to empower students through community-driven career insights.

**Tech Stack:**
- HTML5
- CSS3
- JavaScript

**Links:**
- 🔗 Live: https://nayi-raah.netlify.app/
- 💻 Code: https://github.com/KunalNirmalkar07/Nayi-Raah

---

### 4️⃣ **StudyShare**
**Description:** A collaborative academic platform for students to access and share their collection of academic papers anytime, with secure cloud storage and semester organization.

**Tech Stack:**
- React
- Node.js
- Cloud Storage

**Links:**
- 🔗 Live: https://sharestudydemo.lovable.app
- 💻 Code: https://github.com/KunalNirmalkar07/StudyShare

---

## 🛠️ Tech Stack Used in Portfolio

### Frontend
- HTML5
- CSS3 (Custom Properties, Grid, Flexbox)
- Vanilla JavaScript

### Libraries & Frameworks
- **GSAP** - Advanced animations
- **ScrollTrigger** - Scroll-based animations
- **Lenis** - Smooth scrolling
- **Font Awesome** - Icons
- **Google Fonts** - Typography

### Hosting & Backend
- **Netlify** - Hosting & deployment
- **Netlify Forms** - Contact form backend

---

## 💻 Skills Displayed

### Languages
- HTML5, CSS3, JavaScript
- React.js, Node.js
- Java, Python
- C, C++

### Tools & Technologies
- Docker
- AWS
- Linux
- Git

---

## 📧 Contact Form

The portfolio includes a working contact form that:
- ✅ Collects: Name, Email, Message
- ✅ Has spam protection (honeypot)
- ✅ Sends to Netlify Forms
- ✅ Shows success/error messages
- ✅ Validates all fields

### Setting Up Form Notifications:
1. Deploy site to Netlify
2. Go to Netlify Dashboard → Forms
3. Click "Settings and notifications"
4. Add email notification
5. Enter your email address
6. Save!

Now you'll receive every form submission via email.

---

## 🚀 Deployment Instructions

### Method 1: Netlify Drag & Drop (Easiest)

1. Download all files (index.html, netlify.toml, _redirects)
2. Create a folder called `portfolio`
3. Put all files in that folder
4. Go to https://app.netlify.com/drop
5. Drag the folder onto the page
6. Wait for deployment
7. Your site is live! 🎉

### Method 2: GitHub + Netlify

1. Create a GitHub repository
2. Push all files to the repository root
3. Go to https://app.netlify.com
4. Click "Add new site" → "Import an existing project"
5. Connect GitHub
6. Select your repository
7. Leave build settings empty
8. Deploy!

### Method 3: Netlify CLI

```bash
# Install Netlify CLI
npm install -g netlify-cli

# Navigate to your folder
cd path/to/portfolio

# Deploy
netlify deploy --prod
```

---

## 📱 Sections Included

1. **Hero Section**
   - Animated title
   - Role description
   - Scroll indicator
   - Status indicators

2. **About Section**
   - Bio description
   - Years of experience
   - Expertise areas
   - Call-to-action

3. **Projects Section**
   - 4 featured projects
   - Project images
   - Tech stack tags
   - Live & GitHub links
   - Hover animations

4. **Skills Section**
   - 13 technical skills
   - Icon-based display
   - Staggered animations
   - Organized grid layout

5. **Contact Section**
   - Large call-to-action
   - Social links (GitHub, LinkedIn, Resume)
   - Contact modal form

---

## 🎯 Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers

---

## 📊 Performance

- ⚡ Fast loading time
- 🎨 Smooth animations
- 📱 Fully responsive
- ♿ Accessible
- 🔍 SEO-friendly

---

## 🔗 Social Links

- **GitHub:** https://github.com/KunalNirmalkar07
- **LinkedIn:** https://www.linkedin.com/in/kunal-nirmalkar/
- **Resume:** [Add your resume.pdf to the folder]

---

## 📝 Customization Guide

### Changing Colors
Edit the CSS variables in `<style>` section:
```css
:root {
    --bg: #0b0b0b;        /* Background color */
    --text: #e1e1e1;      /* Text color */
}
```

### Adding More Projects
1. Find the `<section id="projects">` in HTML
2. Copy an existing `<div class="project-item">` block
3. Update the content, links, and tags
4. Update the project count in the section title

### Updating Resume
- Replace `resume.pdf` with your actual resume
- Or update the link in the footer section

### Changing Social Links
- Find the footer section
- Update the `href` attributes with your links

---

## 🐛 Troubleshooting

### Site shows 404
- Make sure files are at root level (not in subfolder)
- File must be named `index.html`
- Check Netlify deploy logs

### Form not working
- Make sure site is deployed first
- Form won't work on localhost
- Set up email notifications in Netlify

### Animations not working
- Check browser console for errors
- Ensure GSAP CDN links are loading
- Try hard refresh (Ctrl+F5)

### Cursor not showing
- Desktop only feature
- Disabled on mobile/touch devices
- Check if CSS `cursor: none` is applied

---

## 📄 License

This portfolio is free to use for personal projects. Feel free to customize it!

---

## 🙏 Credits

### Libraries Used
- GSAP by GreenSock
- Lenis by Studio Freight
- Font Awesome
- Google Fonts

### Design & Development
- Designed & Developed by Kunal Nirmalkar
- Built with ❤️ and lots of ☕

---

## 📞 Support

Need help with deployment or customization?
- Check the `COMPLETE_FIX_GUIDE.md`
- Check the `QUICK_FORM_SETUP.md`
- Visit Netlify documentation

---

## ✅ Deployment Checklist

Before going live:
- [ ] All project links work
- [ ] GitHub username updated everywhere
- [ ] Resume.pdf added
- [ ] Email in LinkedIn/contact updated
- [ ] Test contact form
- [ ] Set up form notifications
- [ ] Test on mobile
- [ ] Check all animations
- [ ] Verify all images load
- [ ] Test all external links

---

## 🎉 That's It!

Your portfolio is ready to showcase your amazing projects to the world!

**Good luck with your job search and project opportunities!** 🚀

---

**Last Updated:** February 2026
**Version:** 1.0
