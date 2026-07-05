# Advocate Avisekh Das Gupta — Portfolio Website

A modern, minimal, and professional personal portfolio website for **Advocate Avisekh Das Gupta**, a practicing lawyer at the **Chattogram Judge Court, Bangladesh**.

The site is a single, self-contained `index.html` file — no build step, no dependencies, no framework. Open it in a browser and it works.

---

## ✨ Features

- **Minimal & premium design** — white/light-gray palette with a deep navy accent (`#1E3A5F`)
- **Editorial typography** — Cormorant Garamond (headings) paired with Inter (body)
- **Subtle, refined animations**
  - Orchestrated hero entrance sequence on page load
  - Staggered fade-in reveals on scroll (cards animate one after another)
  - Timeline line that draws itself in as it enters the viewport
  - Section-title underline draw
  - Scroll progress bar under the top edge
  - Gentle hover micro-interactions (button sheen, icon fills, card lift)
  - Slow ambient sway on the scales-of-justice mark
- **Fully responsive** — desktop, tablet, and mobile with a collapsible menu
- **Accessible** — semantic HTML, keyboard-focus styles, ARIA labels, and full `prefers-reduced-motion` support (all animation disabled for users who request it)
- **SEO ready** — semantic structure, meta description, descriptive title
- **Working contact form** — opens the visitor's email app pre-addressed to the chamber (no backend needed)

## 📄 Sections

1. **Hero** — name, practice areas, introduction, CTAs, and quick highlights
2. **About** — professional introduction and core values
3. **Practice Areas** — Criminal Law, Family Law, Labour Law, and NI Act
4. **Professional Experience** — timeline of practice at the Chattogram Judge Court
5. **Education** — LL.M and LL.B, Premier University
6. **Skills** — legal, technical, and professional competencies
7. **Why Choose Me** — integrity, strategic advocacy, client focus, dedication
8. **Contact** — chamber details and consultation form
9. **Footer** — quick navigation, contact info, and professional disclaimer

## 🚀 Getting Started

### View locally

```bash
git clone https://github.com/<your-username>/avisekh-das-gupta-portfolio.git
cd avisekh-das-gupta-portfolio
```

Then simply open `index.html` in any browser — or serve it locally:

```bash
# Python
python -m http.server 8000

# or Node
npx serve .
```

Visit `http://localhost:8000`.

### Deploy

The site is 100% static, so it deploys anywhere in seconds:

| Platform | How |
|---|---|
| **GitHub Pages** | Repo → Settings → Pages → deploy from `main` branch root |
| **Vercel** | Import the repo — no configuration needed |
| **Netlify** | Drag & drop the folder, or connect the repo |

## 🖼️ Adding a Portrait Photo

The hero currently shows an elegant navy monogram panel as a placeholder. To use a real photograph:

1. Add your photo to the project (e.g. `assets/portrait.jpg`) — a formal portrait in **4:5** ratio works best.
2. In `index.html`, replace the `<div class="portrait">…</div>` block with:

```html
<img class="portrait" src="assets/portrait.jpg"
     alt="Advocate Avisekh Das Gupta" style="object-fit:cover">
```

## 🎨 Customization

All design tokens live in one place at the top of the CSS:

```css
:root{
  --navy:#1E3A5F;      /* accent color */
  --ink:#1A1A1A;       /* primary text */
  --muted:#6B7280;     /* secondary text */
  --bg-soft:#F8F9FA;   /* alternate section background */
  --border:#E5E7EB;
}
```

Change `--navy` to `#1F4D3B` for the dark-emerald variant of the palette.

## 🛠️ Tech

- HTML5 (semantic)
- CSS3 (custom properties, grid, IntersectionObserver-driven reveals)
- Vanilla JavaScript — zero dependencies
- Google Fonts: Cormorant Garamond & Inter

## ⚖️ Disclaimer

This website is intended solely for informational purposes and does not constitute legal advice. Contacting through this website does not create an advocate–client relationship.

## 📬 Contact

**Advocate Avisekh Das Gupta**
Chamber 634, Annex 01, Chattogram Judge Court, Bangladesh
📧 dasguptaavi25@gmail.com · 📞 01798 607183

---

© 2026 Advocate Avisekh Das Gupta. All rights reserved.
