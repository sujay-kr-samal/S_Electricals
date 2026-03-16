# ⚡ S Electrical — Business Website

A clean, modern, fully responsive business website for **S Electrical**, a licensed electrical contractor based in **Siliguri, West Bengal**. Built with pure HTML, CSS, and JavaScript — zero frameworks, zero dependencies.

---

## 🌐 Live Features

- **Landing Page** (`index.html`) — Full business website with enquiry form
- **Admin Panel** (`admin.html`) — Password-protected dashboard to manage enquiries

---

## 📁 Project Structure

```
S_Electricals/
├── index.html        # Main business website
├── admin.html        # Admin panel for managing enquiries
└── assets/
    └── favicon.png   # Site favicon
```

---

## ✨ Website Sections

| Section | Description |
|---|---|
| **Hero** | Bold headline, stats (500+ projects, 10+ years), CTA buttons |
| **Ticker** | Animated scrolling banner of services |
| **Services** | 6 service cards — Residential, Commercial, Industrial, Panel, Inspection, Emergency |
| **Why Us** | Trust badges — Licensed, Transparent Pricing, On-Time, Guarantee |
| **Process** | 4-step process — Contact → Site Visit → Work → Inspection |
| **Contact** | Enquiry form with phone, email, and location info |
| **Footer** | Social links — Instagram, Facebook, WhatsApp |

---

## 🛠️ Admin Panel

Access the admin dashboard at `admin.html`

**Default Credentials:**
| Field | Value |
|---|---|
| Username | `admin` |
| Password | `admin123` |

> ⚠️ Change these credentials before deploying to production!

**Admin Features:**
- 📊 Stats dashboard — Total, New, In Progress, Completed enquiries
- 🔍 Search by name or phone number
- 🏷️ Filter by status — All / New / Read / Done
- ✅ Mark enquiries as Read or Done
- 📞 One-click call button
- 🗑️ Delete enquiries
- 🔄 Auto-refreshes every 10 seconds

---

## 📬 Enquiry Form

When a visitor submits the contact form, the enquiry is saved to `localStorage` with:
- Name, Phone, Email
- Service needed
- Message
- Date & Time
- Status (`new` by default)

All enquiries are instantly visible in the Admin Panel.

---

## 🎨 Tech Stack

| Technology | Usage |
|---|---|
| HTML5 | Structure |
| CSS3 | Styling, animations, grid layout |
| Vanilla JavaScript | Form handling, localStorage, admin logic |
| Font Awesome 6.5 | Icons |
| Google Fonts | Bebas Neue + Barlow typography |

---

## 🚀 Getting Started

No installation needed. Just open in a browser:

```bash
# Clone the repo
git clone https://github.com/sujay-kr-samal/S_Electricals.git
cd S_Electricals

# Open in browser
open index.html
```

Or deploy directly to **GitHub Pages**, **Netlify**, or **Vercel** — it's a static site, no backend needed.

---

## 📱 Responsive Design

Fully responsive across all screen sizes:
- ✅ Desktop
- ✅ Tablet
- ✅ Mobile (nav links hidden on small screens, single column layouts)

---

## 📞 Business Contact

| | |
|---|---|
| 📱 Phone / WhatsApp | +91 95639 02229 |
| 📧 Email | info@selectrical.com |
| 📍 Location | Siliguri, West Bengal |
| 📸 Instagram | [@_s_electrical_](https://www.instagram.com/_s_electrical_/) |

---

## 🔮 Future Improvements

- [ ] Connect form to a real backend (Node.js / Firebase)
- [ ] Add email notifications on new enquiry
- [ ] Google Maps integration
- [ ] WhatsApp chat widget
- [ ] Gallery / portfolio section
- [ ] Customer testimonials / reviews

---

## 👨‍💻 Built By

Made with ⚡ by [Sujay Kr Samal](https://github.com/sujay-kr-samal)

> *"Ship fast. Break things. Fix them. Repeat."*
