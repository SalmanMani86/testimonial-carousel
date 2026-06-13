# Testimonial Carousel

A clean, modern, responsive testimonial carousel built with **vanilla HTML, CSS & JavaScript** — no frameworks, no build step, zero dependencies.

🔗 **Live demo:** https://salmanmani86.github.io/testimonial-carousel/

## Features

- 🎠 **Smooth slider** with polished easing transitions
- ⏯️ **Auto-scroll** (every 5s) — pauses on hover and when the tab is hidden
- 🖱️ **Manual navigation** — arrows, dots, swipe gestures, and ← / → keyboard keys
- 🌓 **Light / dark mode** — toggle button, remembers your choice, respects OS preference
- 👤 **Full testimonial fields** — customer name, role, company, and quote
- 📱 **Fully responsive** — adapts cleanly from mobile to desktop
- ⚡ **Fast & lightweight** — a single self-contained file, GPU-friendly transforms
- ♿ **Accessible** — ARIA roles and `prefers-reduced-motion` support

## Usage

Open `index.html` in any browser — that's it.

To use your own testimonials, edit the `testimonials` array near the top of the `<script>` block:

```js
var testimonials = [
  {
    text: "Your customer's quote here.",
    name: "Jane Doe",
    role: "Marketing Director",
    company: "Acme Inc.",
    color: "#6c8cff"   // avatar background color
  },
  // ...add as many as you like
];
```

## Tech

Plain HTML, CSS custom properties (theming), and a small dependency-free JavaScript module. Works in all modern browsers.
