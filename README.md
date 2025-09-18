# CreativeStudio - Digital Design Agency (Static Website)

A responsive **static website** for a digital design agency, built using only **HTML, CSS, and JavaScript**.  
This version is framework-free (no React, no build tools) and runs natively in the browser.

---

## 🌍 How the Web Works (In Context)

When you open a website like this one, the browser performs several steps:

1. **Request** – Your browser requests files from a web server (`index.html`, `style.css`, `script.js`, plus images and fonts).
2. **HTML Parsing** – The browser reads `index.html`, which provides the **structure** of the page (headings, sections, links, footer).
   - Example: The `<section id="services">` block defines the “Services” section of the page.
3. **CSS Application** – The browser then applies `style.css`, which contains all the **visual design rules**:
   - Fonts (via Google Fonts in `<head>`)
   - Layout (flexbox/grid for services and hero section)
   - Colors, spacing, buttons, and branding
4. **JavaScript Execution** – Finally, `script.js` (optional) runs in the browser to add **behavior**:
   - Could power interactive navigation, form validation, animations, etc.
   - Currently lightweight, so the site is mostly static.
5. **Render** – The rendering engine combines HTML (structure), CSS (style), and JS (behavior) into the interactive page you see.

---

## 🚀 Features

- Semantic **HTML5 structure** for accessibility and SEO
- Responsive layout using **Flexbox/Grid**
- Typography with **Google Fonts (Inter)**
- **Open Graph / Twitter meta tags** for better social sharing
- **Hero section** with CTA buttons
- **Services section** with cards
- Lightweight **footer with links**
- Ready-to-extend JavaScript file (`script.js`)

---

## 📂 Project Structure

.
├── index.html # Main HTML page (structure + content)
├── style.css # Styling and layout rules
├── script.js # Optional JavaScript for interactivity
└── README.md # Documentation

yaml
Copy code

- **index.html** – The page skeleton. Contains header, hero, services, footer.
- **style.css** – All visual styling. Change colors, fonts, spacing here.
- **script.js** – Add your interactive features (menu toggle, animations, etc.).
- **README.md** – Project overview & setup guide.

---

## 📖 Usage

### Run Locally
1. Clone or download this repository.
2. Open `index.html` in any browser.
3. The site should display immediately.

### Deploy Online
- **GitHub Pages** – Push to a GitHub repo → Enable Pages in settings.


---

## ✏️ Customization

- **Brand Identity** – Change the logo text `CS` and branding in `<header>`.
- **Content** – Update hero title, description, and service cards in `index.html`.
- **Theme** – Modify colors and spacing inside `style.css`.
- **JavaScript Features** – Add functionality in `script.js`:
  - Smooth scroll for nav links
  - Mobile navigation menu
  - Form handling or animations

---

## 🖼️ Live Link
https://shiksann.github.io/plp-webtechnologies-classroom-july2025-july-2025-final-project-and-deployment-Final-Project-and-Depl/

---

### 💡 Summary

This website demonstrates how the **core web stack** works:
- **HTML** provides the structure (content & layout).
- **CSS** defines the look and feel (styles & responsiveness).
- **JS** adds interactivity (currently minimal, extendable as needed).

Together, they form the foundation of the modern web.

