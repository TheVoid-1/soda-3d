# 🥤 Diet Soda — 3D Interactive Landing Page

A high-performance, immersive 3D hero landing page for **Diet Soda**, featuring interactive 3D WebGL models, cursor-reactive physics, dynamic flavor transitions, and a modern glassmorphism interface.

[![Live Demo](https://img.shields.io/badge/Live_Demo-Vercel-000000?style=for-the-badge&logo=vercel)](https://diet-soda-zero.vercel.app/)
[![3D Engine](https://img.shields.io/badge/3D_Engine-Google_%3Cmodel--viewer%3E-4285F4?style=for-the-badge&logo=google)](https://modelviewer.dev/)
[![Animation](https://img.shields.io/badge/Motion-GSAP_3-88CE02?style=for-the-badge&logo=greensock)](https://gsap.com/)

---

## 🌐 Live Preview

👉 **[Experience the Live Site](https://diet-soda-zero.vercel.app/)**

---

## ✨ Features

- **🎮 Real-Time 3D Cursor Tilt**: The central 3D soda can dynamically tilts and tracks cursor orientation in real time with smooth lerp interpolation.
- **⚡ Force-Field Berry Repulsion**: Floating 3D berries and botanical leaves drift with multi-layered parallax and are dynamically repelled by the user's cursor.
- **🔄 Dynamic Flavor Switch**:
  - Choreographed 720° spin animation with motion blur using GSAP.
  - Runtime PBR texture swapping (`Diet Classic` ↔ `Zero Lime`).
  - Berries implode to center, swap models (`cherry.glb` ↔ `blueberry.glb`), and explode back into new positions.
  - Smooth radial gradient background morph.
- **🫧 Ambient Micro-Bubbles**: Lightweight continuous bubble generator rising with sinusoidal drift and rotation.
- **🪟 Complete Interactive Glassmorphism UI**:
  - **Shop Now**: Interactive quick-checkout modal with pack selection (Single, 6-Pack, 12-Pack), quantity controls, and dynamic pricing.
  - **Contact Us**: Responsive glass contact form with feedback toast notifications.
  - **Nav Modals**: Full-detail overlays for **Ingredients** (nutrition facts), **Taste** (flavor chemistry & sensory meters), **Eco** (sustainability commitment), and **Reviews** (verified testimonials).
  - **Design Awards**: Interactive badge showcasing international packaging and flavor accolades.
- **🚀 60–120 FPS High Performance**:
  - Cached coordinate tracking to eliminate DOM layout thrashing (`getBoundingClientRect()` removed from render loops).
  - Hardware-accelerated GPU transforms (`translate3d`).

---

## 🛠️ Tech Stack

- **HTML5 & Vanilla JavaScript**: Zero frameworks or bundlers required.
- **CSS3**: Custom properties, backdrop filters, CSS keyframes, and responsive typography.
- **[Google `<model-viewer>`](https://modelviewer.dev/)**: WebGL 3D model rendering, PBR shading, and camera controls.
- **[GSAP 3](https://gsap.com/)**: Timeline management, easing curves, and color interpolation.

---

## 🚀 Getting Started

Clone the repository and open `index.html` in any modern web browser:

```bash
# Clone repository
git clone https://github.com/TheVoid-1/soda-3d.git

# Navigate into directory
cd soda-3d

# Open index.html directly or serve with a local server
npx serve .
```

---

## 📦 Deployment

Deploy effortlessly to Vercel with a single command:

```bash
vercel --prod
```

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
