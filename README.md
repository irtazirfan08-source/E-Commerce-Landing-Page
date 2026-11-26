# Material Flask

Interactive e-commerce landing page for **Material Flask** featuring custom WebGL canvas visuals, a GSAP ScrollTrigger product showcase, an interactive thermal comparison slider, live product configurator with a slide-over bag drawer, customer testimonials, an accessible FAQ accordion, and a newsletter signup section.

Interactive Live Website : https://e-commercelan.netlify.app/

---

## Visuals

| Studio Showcase | Riverside Carry |
| :---: | :---: |
| ![Material Flask Studio Showcase](https://www.gstatic.com/aistudio/starter-apps/flask-applet/flask-showcase-studio.webp) | ![Material Flask Riverside](https://www.gstatic.com/aistudio/starter-apps/flask-applet/flask-showcase-river.webp) |
| **Granite Trail** | **Alpine Dusk** |
| ![Material Flask Trail](https://www.gstatic.com/aistudio/starter-apps/flask-applet/flask-showcase-trail.webp) | ![Material Flask Lakeside](https://www.gstatic.com/aistudio/starter-apps/flask-applet/flask-showcase-lake.webp) |

---

## Features

- **Dismissible Promo Banner & Responsive Header**: Free-shipping announcement bar paired with live bag item counter.
- **Global WebGL Loading Overlay**: Smooth full-screen loader while the hero and engineering spec WebGL canvases initialize.
- **Hero & Social Proof**: Full-bleed WebGL hero section followed by a *"Join 10,000+ adventurers"* avatar trust banner.
- **Pinned Multi-Stage Showcase**: Scroll-driven 4-stage product storytelling powered by GSAP & ScrollTrigger.
- **Interactive Thermal Comparison Slider**: Drag-and-reveal hot vs. cold retention view.
- **Engineering Specs & Testimonials**: Bento feature breakdown, flexbox testimonial cards with GSAP hover scale animations, and 5-star ratings.
- **FAQ Accordion & Newsletter**: Accessible accordion for product care, warranty, and shipping, plus an email signup form with validation.
- **Product Configurator & Bag Drawer**: Choose finish (`Alpine Sage`, `Basalt Black`, `Glacier Silver`) and size (`750 ml`, `950 ml`, `1.2 L`) with live quantity updates in the slide-out bag.
- **Smooth Scrolling & Scroll-to-Top**: Lenis smooth scroll with a floating return-to-top button after scrolling past the hero.

---

## Tech Stack

- **Framework:** React 19 + TypeScript
- **Build Tool:** Vite
- **Animations & Scroll:** GSAP (`ScrollTrigger`), Lenis
- **Graphics:** Custom WebGL2 / 2D Canvas modules (`src/webgl/heroCanvas.ts`, `src/webgl/specsCanvas.ts`)

---

## Run Locally

```bash
# Install dependencies
npm install

# Start development server (http://localhost:3000)
npm run dev

# Type-check
npm run lint

# Build for production
npm run build
```
