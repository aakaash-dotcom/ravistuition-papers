# Ravi's Tuition — TN Papers | Madurai Since 1999

Colourful, fast, student-facing papers portal — Class 6 to 12 • TN Samacheer Kalvi.

**v7 — Colourful Fast Student-Facing**

- 🔍 Search bar on top — hero search + header search
- 🎨 Colourful marketing: 6 cards with icons (📚🎯💬🧠🏫⭐), gradient hero, colourful class cards
- 🔢 Class icons bottom reversed 12→6 — 🎓📐📚🔬🌍✏️🌱 with coloured bars
- ⚡ No Latest Uploads on home (faster LCP) — marketing words instead
- 🔒 Download after login — Name, Phone, Class, District, State
- ☑️ I agree to Terms and Conditions checkbox (Terms link contains everything)

**Features:**
- 16 papers catalogue, real WebP tiles, signed URLs
- Watermarked PDF per user
- Hash router, SEO pages, DPDP compliant legal pages
- Fully inline self-contained index.html (75KB) — works in file preview + live
- Mobile-first LCP <2.5s

**Stack:**
- Single HTML file — no build, no CDN, inline CSS+JS
- Assets: 4 real WebP tiles in /assets/tiles/
- Data: /data/catalogue.json + inline window.SITE_DATA

**Run:**
```bash
python3 -m http.server 3000 --directory .
```

**Deploy:**
- Same domain ravistuition.in — upload index.html + assets/
- Or GitHub Pages / Vercel / Netlify

© 1999–2026 Ravi's Tuition · ravistuition.in | 86106 53352
