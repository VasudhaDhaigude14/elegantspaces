# ElegantSpaces 🛋️ ✨

ElegantSpaces is a high-end, responsive landing page designed for premium interior architectural services. The project blends modern, fluid design aesthetics with exceptional web typography and smooth, hardware-accelerated animations.

## 🎨 Design System & Visuals

The layout utilizes a curated luxury color engine designed to evoke comfort, structure, and prestige:
*   **Primary Canvas:** Deeply muted **Celadon Sage** (`#2C4A40` & `#F8FAF9`) for a fresh, grounded structural feel.
*   **High-Contrast Accent:** Luminous **Electric Royal Violet** (`#6C5CE7`) for modern micro-interactions, buttons, and responsive highlight anchors.
*   **Typography:** Google Fonts' **Poppins** (weights 300 to 700) for clean line profiles and crisp scannability.

---

## ⚡ Core Engineering Features

*   **Fluid Animation Engine:** Implements a hardware-accelerated `IntersectionObserver` script to handle elegant, progressive layout reveals and staggered grid element transitions on scroll.
*   **Pure CSS Float Controls:** Input fields use native CSS adjacent sibling combinators (`~`) to animate placeholders into upper-case labels seamlessly without JavaScript performance costs.
*   **Glassmorphism Overlays:** Portfolio showcases utilize luxury backdrop-filters (`backdrop-filter: blur(8px)`) providing an editorial, high-end look on component hover states.
*   **Elastic Interface Elements:** Accordion systems use cubic-bezier acceleration mapping (`cubic-bezier(0.68, -0.6, 0.32, 1.6)`) to give accordion toggles a snappy, high-fidelity response.
*   **Responsive Blueprint:** Built from the ground up with flexible CSS Grid and Flexbox layouts, making it fully optimized across mobile, tablet, and desktop viewports.

---

## 🛠️ Built With

*   **HTML5** – Semantic element architecture (`<header>`, `<section>`, `<details>`) for strong SEO and accessibility baselines.
*   **CSS3 Custom Variables** – Structured design tokens for colors, animations, and typography easing paths.
*   **Native JavaScript** – Performance-optimized intersection monitoring for scrolling states.
*   **Remix/Feather Inline SVGs** – Clean, ultra-lightweight custom graphics for service structures and layout registries.

---

## 🚀 Live Deployment Workflow

This project is continuously integrated using **Vercel** connected directly to the **GitHub** source engine:
*   **Production Link:** https://interiorhomedecor.vercel.app/ 
*   **Continuous Deployment Pipeline:** Any direct browser modifications committed to the `main` branch will instantly trigger production-optimized serverless rebuilds via Vercel within seconds.
