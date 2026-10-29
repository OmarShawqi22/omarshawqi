<div align="center">

# Omar Shawqi — Portfolio

**A hand-coded, multi-page portfolio for a Computer Science student, founder and freelancer, written in plain HTML, CSS and JavaScript.**

[![Live Site](https://img.shields.io/badge/Live_Site-Visit-38bdf8?style=for-the-badge)](https://omarshawqi7722.github.io/omar-shawqi-portfolio/)
[![GitHub](https://img.shields.io/badge/GitHub-omarshawqi7722-181717?style=for-the-badge&logo=github)](https://github.com/omarshawqi7722)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Omar_Shawqi-0077B5?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/omarshawqi/)

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![GitHub Pages](https://img.shields.io/badge/Hosted_on-GitHub_Pages-222?style=flat-square&logo=githubpages)

</div>

---

## About

This is my personal website. It covers who I am, where I've worked and volunteered, the certificates I've earned and the projects I've built.

I wrote all of it myself without a framework, template or build step. The layouts, animations and interactions are all hand-coded, and the site is a working sample of my front-end skills as much as a CV.

Visitor analytics and contact messages go to a separate **admin dashboard** I built with Next.js, TypeScript, Supabase and Recharts. It's hosted on Vercel, so I can see who visits and which links they click.

---

## Pages

| Page | What's on it |
|------|--------------|
| **Home** (`index.html`) | Hero with typing headline and rotating subtitles, an "Available for Work" badge, skill cards, programming skill bars |
| **About** (`about.html`) | Profile, work experience timeline, volunteering, certificate gallery with viewer, CV download in English and Arabic |
| **Projects** (`projects.html`) | Featured projects with live previews, plus a filterable grid (Software · Business · Academic · Personal) |
| **Contact** (`contact.html`) | Contact cards, social links and a contact form |

---

## Features

**Design**
- Dark navy and electric-cyan theme with an aurora background, glowing orbs and glass panels
- Particle constellation background that drifts toward the cursor
- Cursor spotlight on glass cards and 3D tilt on featured project previews
- Scroll progress bar, scroll-reveal animations and count-up stats
- An experience timeline that fills in as you scroll, and portrait parallax on the About page

**Content**
- **Certificate gallery** showing 17 credentials (Google, UNICEF, DeepLearning.AI, Wharton, University of Helsinki, ICDL and more), grouped by category, with a full-screen viewer that supports keyboard and swipe navigation
- **Project filtering** using animated tabs with a sliding pill indicator
- **Downloadable CVs** in English and Arabic

**Performance and UX**
- Fully responsive with a full-screen mobile menu
- Lighter effects on mobile and low-power devices: fewer blur layers, a single background orb and GPU-composited animations
- Font Awesome loads asynchronously and external resources are preconnected, so neither blocks rendering
- Short fade transitions between pages

**Analytics** (`tracking.js`)
- Records anonymous page visits (entry page, referrer, screen size, language, timezone)
- Detects clicks on WhatsApp, LinkedIn, GitHub, email and CV links automatically
- Sends contact form submissions to the admin dashboard API

---

## Featured Projects

| Project | Type | Links |
|---------|------|-------|
| **Israf Guard**: food-waste management platform | Software · Academic | [Live](https://omarshawqi7722.github.io/isrraaff/) · [Code](https://github.com/OMARSHAWQI7722/isrraaff) |
| **Next Stack**: student tech club website | Software | [Live](https://omarshawqi7722.github.io/next-stack-website/) · [Code](https://github.com/OMARSHAWQI7722/next-stack-website) |
| **OZO Store**: luxury watch and accessories brand | Business | [Visit store](https://ozostore.odoo.com) |
| **Elite Vibes**: digital services store | Business | [Visit store](https://anedstore.odoo.com) |
| **AIU Shop**: campus store | Business | [Visit site](https://www.aiushop.net) |
| **C++ Console Application** | Software · Academic | [Code](https://github.com/OMARSHAWQI7722/Final-project) |
| **Multi-VLAN Campus Network**: VLANs, IP addressing and routing for a segmented campus network | Software · Academic | Coursework project |
| **Smart Refill Station**: eco-friendly campus refill concept with business model and market analysis | Business · Academic | Coursework project |
| **Car Supplier Management System** | Software · Personal | [Code](https://github.com/OMARSHAWQI7722/car-supplier-management-system) |
| **Portfolio V1 / V2**: earlier versions of this site | Software · Personal | [V1](https://omarshawqi7722.github.io/omar-portfolio/) · [V2](https://omarshawqi7722.github.io/omar-shawqi-portfolio-v2/) |

---

## Tech Stack

| Technology | Used for |
|------------|----------|
| **HTML5** | Semantic page structure |
| **CSS3** | Layout, animations, glassmorphism, responsive design |
| **Vanilla JavaScript** | Menu, typing effect, certificate viewer, particles, scroll effects, filtering |
| **Font Awesome 6** | Icons |
| **EmailJS** | Contact form delivery, with a `mailto:` fallback |
| **Next.js + Supabase** (separate repo) | Admin dashboard API for analytics and messages |
| **GitHub Pages** | Hosting |

---

## Project Structure

```
omar-shawqi-portfolio/
├── index.html          # Home
├── about.html          # About, experience, volunteering, certificates, CV
├── projects.html       # Projects showcase with filters
├── contact.html        # Contact page and form
│
├── style.css           # Base styles and Home page
├── refresh.css         # Redesign layer for About / Projects / Contact (namespaced classes)
│
├── script.js           # Menu, typing hero, contact form, transitions, certificate gallery
├── motion.js           # Particles, scroll reveals, tilt, parallax, counters, filters
├── tracking.js         # Visitor and event analytics → admin dashboard
│
├── certificates/       # Certificate images
└── images/
    ├── covers/         # Project cover images
    ├── logos/          # Company and organisation logos
    └── omar-photo.jpg
```

---

## Run Locally

No dependencies and no build step.

```bash
git clone https://github.com/omarshawqi7722/omar-shawqi-portfolio.git
cd omar-shawqi-portfolio
```

Open `index.html` in your browser, or use the **Live Server** extension in VS Code so page transitions and relative links behave exactly as they do online.

> **Contact form:** to send real emails, replace `YOUR_PUBLIC_KEY` in `contact.html` with your EmailJS public key. Until you do, the form opens the visitor's mail app instead.

---

## Contact

| | |
|---|---|
| Email | [7omarshawqi7@gmail.com](mailto:7omarshawqi7@gmail.com) |
| LinkedIn | [linkedin.com/in/omarshawqi](https://www.linkedin.com/in/omarshawqi/) |
| GitHub | [github.com/omarshawqi7722](https://github.com/omarshawqi7722) |
| Instagram | [@7qz_2](https://instagram.com/7qz_2) |
| WhatsApp | [+967 772 291 980](https://wa.me/967772291980) |

---

## License

The code is available under the [MIT License](LICENSE). You're welcome to learn from it and borrow techniques, but please don't publish it as your own portfolio. The personal content (photos, certificates, CVs, logos and text) belongs to me and isn't covered by the license.

---

<div align="center">

Built by **Omar Shawqi**
Computer Science Student @ Albukhary International University, Malaysia

If something here helped you, a ⭐ is appreciated.

</div>
