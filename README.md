# Trivex Laundry — Laundry website

A single-page, animated 3D website for a laundry business in [CITY], Sri Lanka.
Everything lives in `index.html` (Three.js r160, GSAP + ScrollTrigger and Lenis load from CDNs). Every 3D object is built in code, so there are no model files.

## Setup
1. Open `index.html` and fill in the `CONFIG` block at the top of the script: business name, city, address, WhatsApp number, phone, prices and minimum order.
2. To add Sinhala, fill in `CONTENT.si` using the same structure as `CONTENT.en`. A language button appears in the nav once it has content.
3. Host it anywhere static, for example GitHub Pages (Settings → Pages → deploy from `main`).

The booking form opens WhatsApp with the booking details filled in, so no server is needed.
