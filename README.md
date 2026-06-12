# 🚀 Mahi Surani — Personal Portfolio Website

A professional, modern, single-page portfolio website built with pure **HTML5** and **CSS3** — no frameworks, no dependencies.

---

## 📁 Folder Structure

```
mahi-portfolio/
├── index.html        ← Single-page HTML (all sections)
├── style.css         ← Complete stylesheet (~700 lines)
└── README.md         ← This file
```

---

## ✨ Features

| Feature | Details |
|---|---|
| **Responsive** | Mobile-first, works on 320px – 4K |
| **Glassmorphism** | `backdrop-filter` blur cards throughout |
| **Animations** | Scroll-triggered fade-ins, floating hero card, orb parallax |
| **Rotating tagline** | JS-powered role rotation in hero |
| **Skill progress bars** | Animated on scroll reveal |
| **Active nav highlight** | Scrollspy highlights current section |
| **Smooth scrolling** | CSS `scroll-behavior: smooth` |
| **Mobile menu** | Full-screen overlay with animated hamburger |
| **Zero dependencies** | Pure HTML + CSS + vanilla JS |

---

## 🎨 Design Decisions

### Color Palette
- **Background:** Deep navy `#080c14` — professional, tech-forward, easy on eyes
- **Accent:** Teal `#00d4aa` — distinct, modern, cyberpunk-adjacent without being garish
- **Secondary:** Electric blue `#3b82f6` — used for complementary accents
- **Purple:** `#a855f7` — reserved for security-themed project card

### Typography
- **Syne** (display/headings) — geometric, bold, and distinctive; avoids the tired Inter/Roboto look
- **DM Mono** (labels, code, nav) — technical credibility, readable monospace
- **DM Sans** (body) — clean companion to DM Mono, great readability

### Layout Philosophy
- **Asymmetric hero** — code card floating right creates visual interest
- **Section numbering** (01 / About Me) — gives the portfolio a editorial/magazine feel
- **Glassmorphism cards** — depth without heavy gradients; works on the dark background

---

## 🛠️ Sections

1. **Hero** — Full-screen with animated grid, floating orbs, rotating tagline, floating code card
2. **About** — Profile card with pulsing avatar ring + bio with tag cards
3. **Skills** — Grouped skill cards with icons, hover lifts, animated progress bars
4. **Projects** — 3-column card grid with accent stripes, tech tags, status badges
5. **Contact** — Split layout with headline + interactive contact cards
6. **Footer** — Minimal with social icons

---

## 🚀 How to Use

1. Clone or download this repository
2. Open `index.html` in any browser — no build step required
3. Update personal details (email, GitHub URL, LinkedIn URL) in `index.html`
4. Deploy to GitHub Pages, Netlify, or Vercel (drag & drop the folder)

### Deploy to GitHub Pages
```bash
git init
git add .
git commit -m "Initial portfolio commit"
git branch -M main
git remote add origin https://github.com/mahisurani/portfolio.git
git push -u origin main
# Then enable GitHub Pages in repo Settings → Pages
```

---

## 📱 Browser Support

Chrome 88+ · Firefox 87+ · Safari 14+ · Edge 88+

> `backdrop-filter` (glassmorphism) degrades gracefully to solid backgrounds on unsupported browsers.

---

## 📄 License

MIT — free to use as a template. If you find it helpful, a ⭐ on GitHub is appreciated!

---

*Built by Mahi Surani — 2025*
