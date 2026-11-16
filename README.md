# Parthivi Gupta — Personal Portfolio & Resume Website

[![Live Demo](https://img.shields.io/badge/Live_Demo-GitHub_Pages-EA580C?style=for-the-badge&logo=github)](https://parthivi306.github.io/26120920_WD_MTProject/)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/parthivigupta/)

> **Live Website:** [https://parthivi306.github.io/26120920_WD_MTProject/](https://parthivi306.github.io/26120920_WD_MTProject/)  
> **Course:** Web Development Mid-Term Project  
> **Student:** Parthivi Gupta (Roll No: `26120920`)  
> **Program:** BBA (Digital Business &amp; Entrepreneurship), IIM Bangalore  

---

## 📌 Project Overview

This repository contains the source code for my personal resume and portfolio website, designed and built from the ground up using **semantic HTML5** and **modern vanilla CSS3**. 

The website highlights my background in **Growth &amp; Partnerships**, **Case Competition Strategy**, and **Business Development**, showcasing my academic journey at **IIM Bangalore**, corporate internship experience at **RiseUpp**, case challenges with **EY CAFTA** and **DigiYatra**, and leadership roles across the **National Cadet Corps (NCC)**, **Model United Nations (MUN)**, and the **McKinsey Forward Program**.

---

## ✨ Key Features & Sections

- **Sticky Frosted Header:** Features a glassmorphism blur effect (`backdrop-filter: blur(6px)`) with full-coverage page navigation and smooth scrolling (`scroll-behavior: smooth`).
- **Hero Section:** Clear editorial value proposition, quick-facts sidebar card, and direct one-click access to download/view my 1-page PDF resume (`resume.pdf`).
- **About Me:** A two-column responsive grid pairing a formal headshot portrait (`object-fit: cover`) with narrative biography paragraphs.
- **Experience & Projects:** Role timeline with vertical burgundy accent borders, accompanied by modular cards featuring hover-lift micro-interactions (`transform: translateY(-4px)`).
- **Education & Leadership:** Structured tabular timeline and cards highlighting NCC ‘B’ and ‘C’ certifications and Model United Nations awards.
- **Skills Architecture:** Divided into **Digital Tools** (Excel, Canva, Google Sheets, Generative AI) and high-impact **Soft Skills** (Relationship Building &amp; Outreach, Negotiation &amp; Pitching, Structured Problem Solving).
- **Certifications:** Displays my ongoing participation in the prestigious **McKinsey Forward Program** alongside NCC credentials.
- **Contact & Footer:** Full-width high-contrast burgundy banner with direct email and an interactive button linking to my verified **LinkedIn profile**.

---

## 🎨 CSS Architecture & Design Decisions

### 1. Typography Hierarchy
- **Heading Font:** `Playfair Display` (transitional serif) — establishes an authoritative, distinguished editorial aesthetic.
- **Body Font:** `DM Sans` (geometric sans-serif) — guarantees optimal reading comfort and legibility across all screen sizes.
- **Fluid Sizing:** Uses modern `clamp()` (`clamp(2.8rem, 7vw, 5rem)`) for title scaling without abrupt layout jumps.

### 2. Design Tokens (`:root` Palette)
```css
:root {
  --cream: #FFFDF9;      /* Warm, inviting background */
  --ink: #111827;        /* Primary high-contrast text */
  --burgundy: #6E1F2E;   /* Regal heading & container accent */
  --terracotta: #EA580C; /* Interactive CTA & highlight color */
  --sand: #F3EFEA;       /* Subtle card background */
  --muted: #5C6472;      /* Secondary metadata text */
  --line: #E4DDD3;       /* Delicate section divider borders */
}
```

### 3. Layout Systems (Flexbox & CSS Grid)
- **Flexbox:** Drives the single-line responsive header, brand layout, and interactive chip tags (`.chips`).
- **CSS Grid:** Powers the two-column About layout (`260px 1fr`) and resilient auto-fit card grids (`minmax(min(100%, 300px), 1fr)`) that adapt smoothly down to 320px mobile viewports without horizontal overflow.

### 4. Accessibility & Durability
- **WCAG AA Compliance:** Strict color contrast ratios between text and background across all light and dark containers.
- **Reduced Motion Support:** Respects user operating system preferences via `@media (prefers-reduced-motion: reduce)`.
- **Keyboard Navigation:** Clear focus indicator styling via `:focus-visible`.

---

## 📁 Repository Structure

```text
26120920_WD_MTProject/
├── index.html                  # Semantic HTML5 document structure
├── styles.css                  # Custom vanilla CSS design system
├── parthivi.jpg                # Professional headshot portrait
├── resume.pdf                  # 1-page downloadable resume
├── 26120920_WD_MTProject.html  # Formatted assignment report (printable to PDF)
└── README.md                   # Project documentation
```

---

## 🚀 How to Run Locally

1. Clone or download this repository:
   ```bash
   git clone https://github.com/parthivi306/26120920_WD_MTProject.git
   ```
2. Open the folder and double-click `index.html` to launch it directly in any modern browser (Chrome, Edge, Safari, Firefox).
3. No build tools, external dependencies, or node packages are required!

---

## 👩‍💼 Connect with Me

- **Name:** Parthivi Gupta
- **Email:** [parthivigupta306@gmail.com](mailto:parthivigupta306@gmail.com)
- **LinkedIn:** [linkedin.com/in/parthivigupta](https://www.linkedin.com/in/parthivigupta/)
- **College:** Indian Institute of Management Bangalore (IIM Bangalore)

---
*Built with HTML & CSS · © 2026 Parthivi Gupta*
