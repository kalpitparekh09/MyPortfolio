# 🚁 Kalpit Parekh — Drone Cinematographer & Video Editor Portfolio

A cinematic, dark-themed personal portfolio website for **Kalpit Parekh**, a drone cinematographer and video editor. Built with pure HTML, CSS, and JavaScript — no frameworks, no dependencies.

---

## 🌐 Live Site

[https://kalpitparekh.github.io](https://kalpitparekh.github.io)

---

## ✨ Features

- **Cinematic dark UI** — deep navy and black palette with electric cyan accents
- **Animated drone SVG** — floating drone with spinning rotors on the hero section
- **Custom cursor** — glowing cursor with lag-follow ring that reacts to hover
- **YouTube thumbnail integration** — showreel and all portfolio items link directly to YouTube videos
- **Scroll reveal animations** — sections animate in as you scroll down the page
- **HUD-style design elements** — altitude meters, scan lines, grid overlays, and corner decorations
- **Fully responsive** — works on desktop, tablet, and mobile
- **Zero dependencies** — single HTML file, no build tools required

---

## 📁 Project Structure

```
portfolio/
│
├── index.html        # The entire website (HTML + CSS + JS in one file)
└── README.md         # This file
```

---

## 🗂️ Sections

| Section | Description |
|---|---|
| **Hero** | Full-screen intro with animated drone, stats, and CTAs |
| **Showreel** | YouTube thumbnail linking to the 2025 demo reel |
| **Portfolio** | 7-item asymmetric grid of past work, each linking to YouTube |
| **Services** | 6 services offered — aerial cinematography, editing, mapping, and more |
| **Testimonials** | 3 client quotes with author details |
| **Contact** | Enquiry form with email, phone, and location details |

---

## 🎨 Design System

| Property | Value |
|---|---|
| Background | `#080a0e` |
| Surface | `#0d1018` |
| Accent (cyan) | `#00b4ff` |
| Accent (orange) | `#ff6b35` |
| Text | `#e8e4dc` |
| Muted | `#6b7280` |
| Display Font | Bebas Neue |
| Serif Font | Cormorant Garamond |
| Mono Font | DM Mono |

---

## 🛠️ How to Update Content

### Add Your YouTube Videos
Each portfolio item and the showreel use YouTube thumbnail URLs. To update:

1. Find your YouTube video URL — e.g. `https://www.youtube.com/watch?v=abc123xyz`
2. The **Video ID** is the part after `v=` → `abc123xyz`
3. In `index.html`, use `Ctrl+H` to find and replace `VIDEO_ID_2` through `VIDEO_ID_7` with your real IDs
4. The thumbnail will automatically load from: `https://img.youtube.com/vi/YOUR_ID/maxresdefault.jpg`

### Update Contact Details
Search for and replace the following placeholder values in `index.html`:

```
hello@kalpitparekh.film     → your real email
+1 (305) 847-2910           → your real phone number
Based in Miami, FL          → your actual location
```

### Update Stats
In the Hero section, find and edit:
```html
<div class="stat-num">8<span>+</span></div>   <!-- Years Flying -->
<div class="stat-num">240<span>+</span></div>  <!-- Projects -->
<div class="stat-num">30<span>+</span></div>   <!-- Countries -->
```

### Update Social Links
In the Footer, replace the `#` hrefs with your real profile URLs:
```html
<a href="https://instagram.com/kalpit_parekh09">Instagram</a>
<a href="https://youtube.com/@Kalpit_parekh">YouTube</a>
<a href="https://linkedin.com/in/kalpitparekh09">LinkedIn</a>
```

---

## 🚀 Deployment

This site is hosted on **GitHub Pages** for free.

To update the live site after making changes:

```bash
git add .
git commit -m "Update portfolio content"
git push
```

GitHub Pages will automatically rebuild and publish within ~60 seconds.

---

## 📬 Contact

**Kalpit Parekh**
📧 hello@kalpitparekh.film
🌍 Available Worldwide

---

*Built with HTML, CSS & JavaScript · Hosted on GitHub Pages*
