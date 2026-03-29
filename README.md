<div align="center">

```
▸ DRONE CINEMATOGRAPHER & VIDEO EDITOR
```

# KALPIT · PAREKH · FRAMES

### *Capturing the world from perspectives impossible to see on foot*

[![Live Site](https://img.shields.io/badge/LIVE%20SITE-kalpitparekh.me-00b4ff?style=for-the-badge&labelColor=080a0e)](https://kalpitparekh.me)
[![Gallery](https://img.shields.io/badge/PHOTO%20GALLERY-View%20Now-ff6b35?style=for-the-badge&labelColor=080a0e)](https://kalpitparekh.me/gallery.html)
[![YouTube](https://img.shields.io/badge/YouTube-Subscribe-red?style=for-the-badge&logo=youtube&labelColor=080a0e)](https://www.youtube.com/channel/UCo263IKExHDQJvlQ5jgxpyw)
[![Instagram](https://img.shields.io/badge/Instagram-Follow-E1306C?style=for-the-badge&logo=instagram&labelColor=080a0e)](https://www.instagram.com/kalpit_parekh09)

---

```
ALT 400M  ·  Ottawa, Canada  ·  2+ Years Flying  ·  240+ Projects
```

</div>

---

## ▸ About The Site

A cinematic portfolio website for **Kalpit Parekh** — drone cinematographer and video editor based in Ottawa, Canada. Built entirely with vanilla HTML, CSS, and JavaScript. No frameworks, no dependencies, no build tools. Just pure hand-crafted code with a dark cinematic aesthetic inspired by professional film HUDs and aerial photography.

> *"Every cut is purposeful, every transition intentional."*

---

## ▸ Live Preview

| Page | URL |
|---|---|
| 🏠 Main Portfolio | [kalpitparekh.me](https://kalpitparekh.me) |
| 📷 Photo Gallery | [kalpitparekh.me/gallery.html](https://kalpitparekh.me/gallery.html) |

---

## ▸ File Structure

```
kalpitparekh.me/
│
├── index.html          ← Main portfolio page
├── gallery.html        ← Full photo gallery
├── README.md
│
└── images/
    ├── Parliament.jpg
    ├── Night in Ottawa.jpg
    ├── Beach.jpg
    ├── Homes.jpg
    ├── River_View.jpg
    ├── Sunset.jpg
    ├── Snowy.jpg
    ├── Reflection.jpg
    └── ...
```

---

## ▸ Sections

### `index.html`

| Section | Description |
|---|---|
| **Hero** | Full-screen with animated SVG drone, altitude meter, scan line animations |
| **Showreel** | YouTube thumbnail linking to 2025 aerial reel |
| **Photography** | 4-photo auto-responsive teaser → links to full gallery |
| **Selected Work** | 6 YouTube videos in asymmetric 12-column grid |
| **Services** | Cinematic Editing · Real Estate Films · Live Events · Brand & Commercial |
| **Testimonials** | 3 client quotes |
| **Contact** | Email · Phone · Location |

### `gallery.html`

| Feature | Description |
|---|---|
| **Auto-responsive grid** | JS detects each photo's aspect ratio and sizes grid slots accordingly |
| **Category filter** | Aerial · Landscape · Urban · Nature · Golden Hour · Winter · Night |
| **Lightbox** | Fullscreen viewer with keyboard navigation (← → Esc) |
| **Dynamic stats** | Photo count, categories and max altitude computed live from card data |

---

## ▸ Design System

```css
--bg:      #080a0e   /* Deep space black  */
--surface: #0d1018   /* Elevated surface  */
--accent:  #00b4ff   /* Electric cyan     */
--accent2: #ff6b35   /* Burnt orange      */
--gold:    #c9a96e   /* Cinematic gold    */
--text:    #e8e4dc   /* Warm off-white    */
```

**Typography**
- `Bebas Neue` — Display headings
- `Cormorant Garamond` — Body & italic accents
- `DM Mono` — Labels, HUDs, technical text

---

## ▸ Key Features

- 🎯 **Zero dependencies** — Pure HTML · CSS · JavaScript
- 📐 **Auto-responsive photo grid** — Detects landscape / portrait / panoramic / square automatically
- 🖱️ **Custom cursor** — Animated lag-follow ring with blend mode
- 🔭 **Cinematic HUD elements** — Altitude meter, scan lines, viewfinder corners
- 🌓 **Scroll reveal animations** — `IntersectionObserver` powered staggered entrances
- 💡 **Lightbox** — Full-screen photo viewer with arrow key navigation
- 🔢 **Live dynamic stats** — Photo count, categories & max altitude update as images load
- 📱 **Fully responsive** — Mobile breakpoints at 500px and 900px
- 🔗 **SEO ready** — Canonical URLs, Open Graph meta tags, author metadata

---

## ▸ Portfolio Highlights

| Video | Category | Link |
|---|---|---|
| 2025 Showreel | Cinematic | [Watch ↗](https://youtu.be/TsBEpakLTt8) |
| Frozen River | Nature & Wildlife | [Watch ↗](https://youtube.com/shorts/Mw9jN9HYrUk) |
| Snow Covered | Cinematic | [Watch ↗](https://youtube.com/shorts/Aa7WzyGOs6c) |
| Fall Colors | Cinematic | [Watch ↗](https://youtube.com/shorts/GWxZ8dHZeIY) |
| Winter Vibes | Editing | [Watch ↗](https://youtube.com/shorts/XivmdsJjPGs) |
| Planet Earth | Creative | [Watch ↗](https://youtube.com/shorts/Nwh5I3fjNdg) |

---

## ▸ Adding Photos to the Gallery

Copy this block into `gallery.html` inside the `.photo-grid` div:

```html
<div class="photo-card"
     data-src="images/your-photo.jpg"
     data-category="aerial"
     data-title="Your Title"
     data-altitude="350">
  <div class="photo-tag">Aerial</div>
  <div class="photo-corner tl"></div><div class="photo-corner tr"></div>
  <div class="photo-corner bl"></div><div class="photo-corner br"></div>
  <div class="photo-shape-tag"></div>
  <div class="photo-overlay">
    <div class="photo-cat">Aerial</div>
    <div class="photo-title">Your Title</div>
  </div>
</div>
```

> The grid **auto-detects the photo's shape** and sizes it correctly. Stats update automatically.

**Available categories:** `aerial` · `landscape` · `urban` · `nature` · `golden-hour` · `winter` · `night`

**`data-altitude`** = the actual drone altitude in metres when the photo was taken (check EXIF data in your photo properties)

---

## ▸ Services Offered

```
01  Cinematic Editing      — Color grading · Motion graphics · Sound design
02  Real Estate Films      — Drone sweeps · Stabilized shots · Walkthroughs
03  Live Event Coverage    — Concerts · Sports · Festivals · Multi-drone
04  Brand & Commercial     — Automotive · Luxury travel · Advertising campaigns
```

---

## ▸ Contact

<div align="center">

| | |
|---|---|
| 📧 Email | [Kalpitparekh09@outlook.com](mailto:Kalpitparekh09@outlook.com) |
| 📞 Phone | [+1 (905) 782-6760](tel:+19057826760) |
| 📍 Location | Ottawa, Canada — Available Worldwide |
| 🌐 Website | [kalpitparekh.me](https://kalpitparekh.me) |
| 📸 Instagram | [@kalpit_parekh09](https://www.instagram.com/kalpit_parekh09) |
| 🎬 YouTube | [Kalpit Parekh](https://www.youtube.com/channel/UCo263IKExHDQJvlQ5jgxpyw) |
| 💼 LinkedIn | [kalpit-parekh-09](https://www.linkedin.com/in/kalpit-parekh-09/) |

</div>

---

<div align="center">

```
© 2025 Kalpit Parekh — All rights reserved
```

*Built with HTML · CSS · JavaScript — Hosted at kalpitparekh.me*

</div>
