# Czar Consultancy — Official Website

> Labour Law, Compliance & HR Advisory — Pan India

Live website for **Czar Consultancy**, a professional labour law and compliance advisory firm based in Gurugram, India.

---

## 🌐 Live Site

Deployed on Vercel → [your-domain.vercel.app](https://your-domain.vercel.app)

---

## 📁 Files

| File | Purpose |
|------|---------|
| `index.html` | Main website (all pages in one file) |
| `admin.html` | Password-protected admin panel |
| `logo.png` | Company logo (watermark-free version) |
| `README.md` | This file |

---

## ✨ Features

- Multi-page single-file website (Home, About, Services, Team, Contact, Careers)
- 3D ambient particle network (Three.js) in hero and key sections
- Scroll progress indicator & parallax hero image
- 3D tilt interaction on cards
- Live enquiry forms → email via **Formspree** + WhatsApp via **CallMeBot**
- Job listings with apply form (Careers page — toggle visible in admin)
- Password-protected admin panel to manage all content

---

## ⚙️ Admin Panel

Access at: `yoursite.com/admin.html`

**Default password:** `czar2025`
*(Change it in `admin.html` → look for `const ADMIN_PASSWORD`)*

### What you can manage:
- Homepage text (hero heading, descriptions)
- Services (add, edit, delete, reorder)
- Team members (names, roles, bios, photos)
- Job openings (add, toggle active/hidden, enable Careers nav)
- Contact info (phone, email, office addresses)

---

## 📧 Enquiry System

| Channel | Service | Status |
|---------|---------|--------|
| Email | Formspree (`/f/mrevjzbw`) | ✅ Live |
| WhatsApp | CallMeBot | ⏳ Setup pending |

To complete WhatsApp setup, add your API key in `index.html`:
```js
const WA_PHONE  = 'YOUR_WHATSAPP_NUMBER';
const WA_APIKEY = 'YOUR_CALLMEBOT_APIKEY';
```

---

## 🚀 Deployment

Static HTML site — no build step, no framework, no database needed.

**To deploy updates:**
1. Edit files locally
2. Push to this GitHub repo
3. Vercel auto-deploys within ~20 seconds

**To connect custom domain:**
Vercel → Project → Settings → Domains → add `czarconsultancy.in`
Then update nameservers in Hostinger hPanel to point to Vercel.

---

## 🎨 Brand

| Token | Value |
|-------|-------|
| Primary Red | `#CC0000` |
| Ink / Black | `#0D0D0D` |
| Background | `#F8F8F6` |
| Serif Font | EB Garamond |
| Sans Font | Inter |

---

## 📞 Contact

**Czar Consultancy**
- 📧 yashpundeer0@gmail.com
- 📱 +91 9999898370
- 📍 Gurugram, Haryana & New Delhi

---

*Built with plain HTML, CSS & JavaScript. No frameworks. No dependencies except Three.js (CDN) and Google Fonts.*
