# AyOTravelers — Official Website

> **Live:** https://www.ayotravelers.lk  
> **Status:** Production  
> **Region:** Sri Lanka 🇱🇰

AyOTravelers is a modern day-out & tours platform built for Sri Lankan and international travelers. The site showcases curated trips, transparent pricing, WhatsApp inquiries, customer reviews, and a secure admin portal for managing content.

> **Note:** This repository hosts the public documentation and issue tracker only.  
> The application source code is **private** as this is a paid/commercial project.

---

## ✨ Highlights

- **Fast, mobile-first** Next.js 15 frontend with modern UI/UX  
- **SEO-ready** (sitemap, robots, meta, clean URLs)  
- **Image optimization** via Cloudinary CDN  
- **Trip catalog** (destinations, sessions, packages)  
- **Online inquiries & purchase workflow**  
- **Sitewide reviews & ratings**  
- **Secure Admin Portal** (protected routes, cookie auth)  
- **Production hosting** (Vercel + Koyeb), custom domain on `.lk`

---

## 🔗 Important Links

- 🌐 Website: https://www.ayotravelers.lk  
- 🛠 API (Managed): https://api.ayotravelers.lk  
- 📧 Business Contact: supunprabodha0915@gmail.com  
- 📱 Instagram: https://www.instagram.com/ayotravelers  
- 👍 Facebook: https://www.facebook.com/share/1Eet6TJ84w/

---

## 🧱 Tech Stack

- **Frontend:** Next.js 15 (App Router), React 19, Tailwind CSS  
- **API:** Node.js (Express), TypeScript, MongoDB (Atlas)  
- **Media:** Cloudinary  
- **Infra:** Vercel (web), Koyeb (API), register.lk DNS  
- **Auth (admin):** Signed cookie + middleware guard  
- **CI/CD:** GitHub → Vercel/Koyeb auto deploys  

---


bash```
    Users ──▶ Vercel (Next.js web) ──▶ API Proxy Routes (/api/admin/*)
    │
    └────────────▶ Koyeb (Node/Express API) ──▶ MongoDB Atlas
    │
    └──▶ Cloudinary (images)
    ```

- Public pages fetch read-only data from the API.  
- Admin pages call API via protected proxy routes with server-side keys.  
- Images are optimized and delivered via Cloudinary.  

---

## 🔒 Source Code Access

This is a **commercial/paid** project. The source code is not publicly distributed.  

- For demonstrations, partnerships, or a code review under NDA, email  
  **supunprabodha0915@gmail.com** with your details and purpose.  

---

## 📸 Screenshots (Placeholders)

> Replace these with actual images if you want visuals on the repo.

- **Home / Hero:** `/docs/screens/home-hero.png`  
- **Trips Grid:** `/docs/screens/trips-grid.png`  
- **Trip Detail:** `/docs/screens/trip-detail.png`  
- **Admin Dashboard:** `/docs/screens/admin-dashboard.png`  

---

## 🧭 Roadmap

- Multilingual support (සිංහල / English / Deutsch)  
- Rich analytics dashboard (admin)  
- Availability calendar & advanced filters  
- Enhanced review moderation  
- Micro-interactions & performance tuning  

---

## 🐞 Issues & Feedback

Found a bug on the live site or have a feature request?

1. Open a GitHub issue in this repo with clear reproduction steps (URL, device, screenshot).  
2. Or email: **supunprabodha0915@gmail.com**  

---

## 📄 License

All rights reserved.  
This repository’s content (text, images, branding) is proprietary to **AyOTravelers**.  
No redistribution, copying, or reuse without written permission.  

---

## 🙌 Credits

- Built by the **AyOTravelers** engineering team.  
- Special thanks to our early users & partners who shaped the product.  

---

### Press / Business Inquiries

For media kits, partnerships, or bulk bookings:  
**supunprabodha0915@gmail.com**


## 🗺 Architecture (High-Level)

