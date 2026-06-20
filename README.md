# Mohamed Mostafa — Portfolio Website

A personal portfolio website for **Mohamed Mostafa**, an Aerospace Engineer specializing in aerodynamic design, structural analysis, embedded systems, and mechanical engineering for fixed-wing aircraft and Formula 1 racing technology.

**Live Site:** [https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/](https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/)

---

## 📋 Overview

This is a fully responsive, single-page portfolio built with vanilla HTML, CSS, and JavaScript — no frameworks, no build step. It's designed to showcase engineering projects with mixed media (photos and videos), a clear services breakdown, and a working contact form.

## ✨ Features

- **Responsive design** — adapts cleanly across mobile, tablet, and desktop breakpoints
- **Animated hexagonal profile image** using SVG masking and patterns
- **Sticky header with scroll-blur effect** and active-link highlighting tied to scroll position
- **Mobile navigation menu** with toggle/close controls
- **Services section** — always-visible cards listing core service offerings
- **Projects section** with:
  - Stacked project cards, each containing a photo/video gallery and two write-ups (*The Project* and *My Role*)
  - Mixed-media galleries — any gallery box can hold a photo or a video
  - A custom "big photo + two stacked photos" gallery layout for 3-image projects
  - Click-to-expand lightbox for both photos and videos
- **Working contact form** powered by [EmailJS](https://www.emailjs.com/) — no backend required
- **Scroll-to-top button** that appears after scrolling
- **Custom scrollbar styling**

## 🛠️ Built With

| Technology | Purpose |
|---|---|
| HTML5 | Page structure and semantics |
| CSS3 | Styling, responsive layout (CSS Grid/Flexbox), custom properties |
| JavaScript (Vanilla ES6) | Interactivity — menus, lightbox, scroll effects, form handling |
| [Remix Icon](https://remixicon.com/) | Icon set |
| [EmailJS](https://www.emailjs.com/) | Client-side contact form email delivery |
| [Google Fonts — Poppins](https://fonts.google.com/specimen/Poppins) | Typography |

## 📁 Project Structure

```
├── index.html              # Main page markup
├── assets/
│   ├── css/
│   │   └── styles.css      # All site styling
│   ├── js/
│   │   └── main.js         # Interactivity (menu, lightbox, scroll, form)
│   └── img/
│       ├── icon.png        # Favicon
│       ├── profile.png     # Profile photo used in Home/About
│       └── ...              # Project gallery images
│   └── video/
│       └── ...              # Project gallery videos
└── README.md
```

## 🚀 Getting Started

### Run it locally

1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR-USERNAME/YOUR-REPO-NAME.git
   ```
2. Open the folder and launch `index.html` in your browser — no build tools or server required.

### Deploy your own copy

This site is static and deploys for free with **GitHub Pages**:

1. Push the repo to GitHub.
2. Go to **Settings → Pages**.
3. Under "Build and deployment," set Source to **Deploy from a branch**, branch `main`, folder `/ (root)`.
4. Your site will be live at `https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/`.

## ⚙️ Customization

| To change... | Edit... |
|---|---|
| Accent color | `--hue` and `--first-color` variables in `styles.css` |
| Profile photo | Replace `assets/img/profile.png` (recommended: portrait orientation) |
| Services offered | `services__card` blocks in `index.html` |
| Projects | Duplicate a `projects__card` block in `index.html` and update gallery images/videos and text |
| Contact form | Replace the `service_id`, `template_id`, and public key in the `emailjs.sendForm()` call in `main.js` with your own [EmailJS](https://www.emailjs.com/) credentials |

## 📬 Contact

**Mohamed Mostafa** — Aerospace Engineer

- LinkedIn: [linkedin.com/in/aero-mohamed-mostafa](https://www.linkedin.com/in/aero-mohamed-mostafa)
- GitHub: [github.com/Aero-160](https://github.com/Aero-160)
- Facebook: [facebook.com/share/1Yi3FXftsX](https://www.facebook.com/share/1Yi3FXftsX/)

## 📄 License

This project is open for personal reference and learning. If you reuse the layout or code structure, a credit back to this repository is appreciated.
