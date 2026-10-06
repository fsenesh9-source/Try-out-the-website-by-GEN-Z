# ✦ VELORA BEAUTY STUDIO — PREMIUM LUXURY SALON WEBSITE DEMO

> **An agency-grade, ultra-modern luxury website template engineered specifically for selling web design & appointment booking solutions to high-end salons, hairdressers, barbershops, beauty studios, and luxury spas.**

---

## 🌟 Live Demo Preview

- **Local Server**: [http://localhost:8080](http://localhost:8080)
- **Zero Build Step Required**: Open `index.html` directly in any browser or run with any static HTTP server.

---

## 💎 Design & Visual Philosophy

- **Editorial Luxury Aesthetic**: Inspired by high-fashion Milanese ateliers and top global creative agencies (*Pentagram, Locomotive, Studio Freight*).
- **Sophisticated Neutral Palette**: Soft ivory (`#FAF8F5`), crisp white (`#FFFFFF`), warm sand (`#F3EFEA`), deep charcoal slate (`#171615`), and refined champagne gold accents (`#C5A880`).
- **Typography Pairing**: *Cormorant Garamond* (haute couture editorial serif) paired with *Plus Jakarta Sans* (clean geometric legibility).
- **Cinematic Photography**: Curated, photorealistic imagery showing master stylists, balayage application, modern interior suites, treatments, and bridal styling.
- **Micro-Interactions**: Slow Ken Burns hero panning, magnetic button transitions, scroll-triggered counter animations, and celebratory booking confetti.

---

## 🚀 Key Conversion & Interactive Features

### 1. Interactive 6-Step Online Booking Experience
- **Step 1 — Choose Service**: Interactive cards showing starting price, duration, category badge, and instant selection.
- **Step 2 — Choose Stylist**: Cards for each specialist (*Sofia, Marco, Elena, Giulia*) or *"Any Available Stylist"*.
- **Step 3 — Interactive Date Calendar**: Live monthly grid with today highlights, disabled past dates, and closed-Sunday logic.
- **Step 4 — Available Time Slots**: Selectable morning, afternoon, and evening slots (`09:00`, `10:00`, `11:30`, `13:00`, `14:30`, `16:00`, `17:30`).
- **Step 5 — Client Information & Promo Code**: First & last name, phone, email, styling notes, and live promo code engine (`WELCOME20` applies an instant 20% discount).
- **Step 6 — Confetti Confirmation Screen**: Shows booking reference code (e.g., `VB-849201`), appointment recap, *"Add to Calendar (.ics)"* generator, and *"Book Another"* action.

### 2. Interactive Before & After Transformation Slider
- Smooth drag-and-touch split view using high-performance CSS `clip-path`.
- Tab switcher between transformations (*Dimensional Balayage Melt* & *Liquid Silk Keratin Restructure*).
- Direct *"Get This Look"* shortcut leading straight into booking.

### 3. Fullscreen Lookbook Lightbox
- High-res modal preview with zoom, category badges, keyboard navigation (`Escape`, `←`, `→`), and direct booking shortcut.

### 4. Client Testimonials Carousel
- 5-star ratings, realistic client feedback (*Martina, Sofia, Giulia*), verified badges, treatment tags, and auto-play with pause-on-hover.

### 5. Sticky Navigation & Mobile Experience
- Nav shrinks and activates glassmorphism backdrop blur on scroll.
- Animated mobile fullscreen slide-out drawer menu.
- Sticky bottom mobile booking bar with 1-tap booking access.

---

## 🛠️ White-Label Customization System (`js/salon-config.js`)

The entire website is data-driven from a single, clean file: `js/salon-config.js`. You can rebrand the entire site for any client in less than 5 minutes without touching the HTML markup:

| Field | Description |
|---|---|
| `brand.name` | Salon Name (e.g. *"Velora Beauty Studio"*) |
| `brand.tagline` | Tagline (e.g. *"Your Beauty. Your Style. Your Confidence."*) |
| `brand.currency` | Currency symbol (`€`, `$`, `£`, `CHF`, etc.) |
| `contact.fullAddress` | Salon physical address |
| `contact.phone` | Telephone number with click-to-call link |
| `contact.email` | Contact email with click-to-email link |
| `hours` | Opening hours per day (Mon–Fri, Sat, Sun) |
| `stats` | Years experience, happy clients, team members, rating |
| `services` | Array of services (name, price, duration, image, description) |
| `team` | Stylist names, roles, specialties, photos, bios, Instagram links |
| `transformations` | Before/After image pairs, techniques, and stylist tags |
| `gallery` | Lookbook items with categories and high-res imagery |
| `reviews` | Client reviews, star ratings, and avatars |
| `specialOffer` | Promo headline, discount amount, and promo code |

---

## 🎯 Pitching This Demo to Salon Owners (Agency Sales Guide)

When presenting this website demo to prospective salon, hairdresser, or spa clients:

1. **Open the Live Demo on Desktop or Tablet**: Show the full-screen hero with subtle movement and the 4.9/5 trust indicator.
2. **Demonstrate the "Book Your Visit" Flow**:
   - Click **[BOOK YOUR APPOINTMENT]**.
   - Walk through Steps 1 to 6 in under 30 seconds.
   - Point out how easy it is for clients to choose their service, stylist, date, and time.
   - Show the final confirmation screen and click **"Add to Calendar (.ics)"**.
   - *Key Agency Selling Point*: *"Salons lose up to 40% of bookings after 7:00 PM when phones are closed. This online booking engine captures clients 24/7."*
3. **Show the Before & After Slider**:
   - Drag the slider live. Salon owners love showing visual proof of their color and styling skills.
4. **Use the "Demo Controls" Floating Panel**:
   - Click the **Demo Controls** button in the bottom-left corner.
   - Switch between **Velora (Milan)**, **Aurelia (London)**, **The Heritage (NYC Barber)**, or **Elysian (Paris Day Spa)**.
   - Type the salon owner's real business name into the *"Live Salon Name"* box and watch the entire site update in real time!
   - This single feature usually closes the sale on the spot.

---

## 📂 File Architecture

```
project/
├── index.html          # Semantic HTML5 layout with Tailwind CSS & Google Fonts
├── css/
│   └── style.css       # Luxury editorial CSS, animations, clip-path slider, modal styles
├── js/
│   ├── salon-config.js # Central white-label configuration & live demo presets
│   └── app.js          # Booking engine, confetti, stats counter, lightbox, carousel
└── README.md           # Documentation & agency sales pitch guide
```

---

*Copyright © 2026 Velora Beauty Studio. Designed for elite salon web design presentations.*
