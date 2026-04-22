# 🏫 Devine Secondary School — Official Website

> **Excellence · Integrity · Faith** — Est. 2001, Harare, Zimbabwe

[![Website](https://img.shields.io/badge/Live%20Site-Visit%20Now-gold?style=for-the-badge)](https://CMABOSSNATION.github.io/devine-secondary-school)
[![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)](LICENSE)
[![HTML5](https://img.shields.io/badge/HTML5-Single%20File-E34F26?style=for-the-badge&logo=html3)](index.html)
[![WhatsApp](https://img.shields.io/badge/WhatsApp-Contact%20Us-25D366?style=for-the-badge&logo=whatsapp)](https://wa.me/263771234567)

---

## 📌 Table of Contents

- [About the Project](#-about-the-project)
- [Live Demo](#-live-demo)
- [Features](#-features)
- [File Structure](#-file-structure)
- [How to Deploy](#-how-to-deploy)
- [How to Customize](#-how-to-customize)
- [WhatsApp Integration](#-whatsapp-integration)
- [Adding Real Photos](#-adding-real-photos)
- [Google Maps Integration](#-google-maps-integration)
- [Contact](#-contact)

---

## 📖 About the Project

This is the **official website** for Devine Secondary School — a modern, fully responsive, single-page school website built with pure **HTML5, CSS3, and Vanilla JavaScript**. No frameworks, no dependencies, no build tools required. It works directly from a single `index.html` file.

The website was designed to:
- Attract prospective students and parents
- Showcase academic programs and school achievements
- Handle online admissions enquiries
- Provide instant WhatsApp contact for parents

---

## 🌐 Live Demo

🔗 **[https://CMABOSSNATION.github.io/devine-secondary-school](https://CMABOSSNATION.github.io/devine-secondary-school)**

> ⚠️ Update this link after enabling GitHub Pages in your repository settings.

---

## ✅ Features

| Section | What It Does |
|---|---|
| 🔝 Fixed Navbar | Sticky navigation with mobile hamburger menu |
| 🦸 Hero Section | Full-screen welcome with animated stats |
| 📢 News Ticker | Auto-scrolling announcements bar |
| 🏛️ About Section | School story, values, and national rating |
| 📚 Programs | 6 academic program cards with subject tags |
| 🏆 Why Devine | Premium feature highlights (staff, labs, results) |
| 📰 News & Events | Featured news + latest announcements |
| 🖼️ Gallery | Interactive photo grid with hover overlays |
| 👩‍🏫 Staff Profiles | Leadership team showcase |
| 📝 Admissions | 5-step process + online enquiry form |
| 📞 Contact | Address, phone, email, office hours |
| 💬 WhatsApp Card | Branded WhatsApp contact section |
| 💬 WhatsApp Float | Pulsing floating WhatsApp button (every page) |
| 🎉 Form Modal | Success popup with WhatsApp redirect |
| 📱 Mobile Responsive | Fully responsive on all screen sizes |
| ✨ Scroll Animations | Reveal animations on all sections |

---

## 📁 File Structure

```
devine-secondary-school/
│
├── index.html                  ← Entire website (HTML + CSS + JS in one file)
├── README.md                   ← This file
├── LICENSE                     ← MIT License (optional)
│
└── assets/                     ← Add this folder when you have real media
    ├── favicon.ico             ← School logo as favicon (32x32px)
    ├── images/
    │   ├── logo.png            ← School logo (transparent PNG)
    │   ├── hero-bg.jpg         ← Hero background photo
    │   ├── about-photo.jpg     ← School building or students photo
    │   ├── principal.jpg       ← Headmistress photo
    │   └── gallery/
    │       ├── campus.jpg
    │       ├── sports.jpg
    │       ├── science-lab.jpg
    │       ├── computer-lab.jpg
    │       └── library.jpg
    └── docs/
        ├── school-fees-2025.pdf
        ├── prospectus-2025.pdf
        └── term-dates-2025.pdf
```

> 💡 **Note:** The `assets/` folder is optional for the first launch. The website works perfectly without it — all placeholders and emoji icons are built in. Add real images when you have them.

---

## 🚀 How to Deploy

### Option A — GitHub Pages (Free, Recommended)

1. **Create a GitHub account** at [github.com](https://github.com) if you don't have one
2. **Create a new repository** named `devine-secondary-school`
3. Tap **Add file → Create new file**
4. Name the file `index.html`
5. Paste the entire content of `index.html` into the editor
6. Scroll down → tap **Commit new file**
7. Go to **Settings → Pages**
8. Under *Source*, select **Deploy from a branch**
9. Choose **main** branch → **/ (root)** → Save
10. Wait ~2 minutes → your site is live at:
    ```
    https://CMABOSSNATION.github.io/devine-secondary-school
    ```

### Option B — Custom Domain (e.g. devinesecondary.ac.zw)

1. Follow Option A first
2. In **Settings → Pages → Custom domain**, enter your domain
3. At your domain registrar, add a **CNAME record**:
   - Name: `www`
   - Value: `CMABOSSNATION.github.io`
4. Also add **A records** pointing to GitHub's IPs:
   ```
   185.199.108.153
   185.199.109.153
   185.199.110.153
   185.199.111.153
   ```
5. Enable **Enforce HTTPS** in Pages settings

---

## 🎨 How to Customize

All customization is done inside `index.html`. Open it in GitHub's editor and find these sections:

### Change School Name / Motto
Search for `Devine Secondary School` and replace with your exact school name.  
Search for `Excellence · Integrity · Faith` to update the motto.

### Change Colors
Find the `:root` block near the top of the `<style>` tag:
```css
:root {
  --navy: #0a1628;       /* Main dark color */
  --gold: #c9a84c;       /* Accent / highlight color */
  --gold-light: #e8c96b; /* Lighter accent */
  --cream: #f8f4ed;      /* Background */
}
```
Replace `#0a1628` and `#c9a84c` with your school's brand colors.

### Update Statistics (Hero Section)
Search for `1,200+` and update all four stats:
```html
<div class="stat-num">1,200+</div>  ← Total students
<div class="stat-num">98%</div>     ← Pass rate
<div class="stat-num">60+</div>     ← Number of staff
<div class="stat-num">24</div>      ← Years established
```

### Update Announcement Ticker
Search for the `<div class="ticker">` block and replace the `<span>` items with real school announcements.

### Update Staff Cards
Search for `Mrs. G. Moyo` and replace all four staff cards with real staff names, roles, and qualifications.

### Update News Section
Search for `Devine Wins National Science Olympiad` and replace with real school news.

---

## 💬 WhatsApp Integration

The WhatsApp number used throughout this site is:

```
+263 771 234 567
```

To update it to the real school number, do a **Find & Replace** in the file:

- Find: `263771234567`
- Replace with: `263XXXXXXXXX` (your real number without + or spaces)

WhatsApp links appear in **4 places**:
1. Floating bubble (bottom-right of every page)
2. Admissions section green button
3. Contact section branded WhatsApp card
4. Form success modal popup

The link format used is:
```
https://wa.me/263771234567?text=Hello%2C%20I%20have%20an%20enquiry.
```
You can change the pre-filled message by editing the `?text=` part.

---

## 🖼️ Adding Real Photos

The gallery currently uses coloured placeholder blocks. To add real photos:

1. Upload your images to the `assets/images/gallery/` folder on GitHub
2. In `index.html`, find the gallery section and replace each `<div class="gallery-bg cX">` with:

```html
<img src="assets/images/gallery/campus.jpg" 
     alt="School Campus" 
     style="width:100%;height:100%;object-fit:cover;" />
```

Do the same for the About section and staff profile pictures.

---

## 🗺️ Google Maps Integration

The contact section has a map placeholder. To add a real Google Map:

1. Go to [maps.google.com](https://maps.google.com)
2. Search for your school's address
3. Click **Share → Embed a map → Copy HTML**
4. In `index.html`, find this block:
```html
<div class="map-placeholder">
  <span>🗺️</span>
  <p>Embed Google Maps here...</p>
</div>
```
5. Replace the entire `<div class="map-placeholder">` with the `<iframe>` code from Google, adding `style="width:100%;height:100%;border:none;"` to it.

---

## 📄 Adding Downloadable Documents

To let parents download the fees schedule or prospectus:

1. Upload PDF files to `assets/docs/` on GitHub
2. Add a download link anywhere in `index.html`:
```html
<a href="assets/docs/school-fees-2025.pdf" 
   download 
   class="btn-primary">
  📥 Download Fees Schedule
</a>
```

---

## 📞 Contact

| Channel | Detail |
|---|---|
| 📍 Address | 123 Devine Road, Harare, Zimbabwe |
| 📞 Phone | +263 242 123 456 |
| 💬 WhatsApp | [+263 771 234 567](https://wa.me/263771234567) |
| ✉️ Email | info@devinesecondary.ac.zw |
| 🕘 Office Hours | Mon–Fri 7:30AM–4:30PM · Sat 8AM–12PM |

---

## 📜 License

This project is licensed under the **MIT License** — you are free to use, modify, and distribute it for the school's purposes.

---

<div align="center">

**© 2025 Devine Secondary School · Harare, Zimbabwe**  
*Excellence · Integrity · Faith*

Built with ❤️ · Hosted on GitHub Pages

</div>
