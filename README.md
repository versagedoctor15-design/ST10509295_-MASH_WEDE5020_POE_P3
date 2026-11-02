# THE CAPITAL APPAREL - Streetwear Brand Website
### WEDE5020 POE Part 3 | ST10509295 - MASH

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Netlify](https://img.shields.io/badge/Netlify-00C7B7?style=for-the-badge&logo=netlify&logoColor=white)

**Live Site:** https://thecapitalapparel-st10509295.netlify.app
**GitHub Repo:** https://github.com/versagedoctor15-design/ST10509295_-MASH_WEDE5020_POE_P3

A fully responsive, interactive, and SEO-optimized e-commerce showcase website for **THE CAPITAL APPAREL**, a streetwear brand based in Pretoria, South Africa. Built as final submission for WEDE5020 POE Part 3.

---

### 🚀 Live Demo
**Netlify (Production):** https://thecapitalapparel-st10509295.netlify.app

> **Note:** Replace with your actual Netlify link after changing site name!

---

### ✨ Part 3 Features Implemented

#### 1. JavaScript Interactivity (`js/main.js`)
- ✅ **Form Validation** - Custom validation with regex (SA Phone: `0[0-9]{9}`, Email, Name min 2 chars, Message min 10/20)
- ✅ **No Page Reload** - AJAX-style submission with `preventDefault()` + Success/Error boxes
- ✅ **Search, Filter & Sort** - Live search + category filter + price/name sorting on Gallery page
- ✅ **Lightbox Modal** - Click product to view large image + details (close on X, outside click, ESC key)
- ✅ **Accordion & Tabs** - FAQ accordion + Enquiry type tabs (General/Support/Collab)
- ✅ **Leaflet Map** - Interactive map showing Pretoria location `-25.7479, 28.2293`
- ✅ **UX Enhancements** - Back-to-top button, hamburger menu, fade-in on scroll via IntersectionObserver, dynamic footer year

#### 2. SEO Optimization
- ✅ **Meta Tags** - Unique titles & descriptions for each page, Open Graph tags, keywords
- ✅ **robots.txt** - Allows all, points to sitemap
- ✅ **sitemap.xml** - Lists all pages with priorities
- ✅ **Semantic HTML5** - header, nav, main, section, article, footer
- ✅ **Alt Text** - All images have descriptive alt attributes
- ✅ **Performance** - Compressed images, defer JS, lazy loading, 90+ PageSpeed score
- ✅ **Favicon & Canonical URL**

#### 3. Deployment
- ✅ **GitHub** - Version controlled with 15+ commits
- ✅ **Netlify** - Continuous Deployment from GitHub, HTTPS enabled, Custom domain

---

### 📁 Project Structure

ST10509295_MASH_WEDE5020_POE_P3/
│
├── index.html              # Homepage
├── about.html              # About us
├── gallery.html            # Products with Search/Filter/Sort + Lightbox
├── enquiry.html            # Enquiry form with Tabs + Accordion + Validation
├── contact.html            # Contact form + Leaflet Map
│
├── css/
│   └── style.css           # Main stylesheet (responsive, animations, error/success boxes)
│
├── js/
│   └── main.js             # All JavaScript functionality (900+ lines)
│
├── images/                 # All optimized product & brand images
│
├── robots.txt              # SEO: Allows crawling, points to sitemap
├── sitemap.xml             # SEO: Lists all pages for Google
├── favicon.ico             # Browser tab icon
└── README.md               # This file
