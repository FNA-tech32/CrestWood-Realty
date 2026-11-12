# 🏡 CrestWood Realty — Modern Real Estate Platform

<p align="center">
  <img src="https://images.unsplash.com/photo-1600585154340-be6161a56a0c?w=1200&h=500&fit=crop" alt="CrestWood Realty Banner" width="100%" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Brand-CrestWood%20Realty-e8590c?style=for-the-badge&logo=homeadvisor" />
  <img src="https://img.shields.io/badge/HTML5-Semantic%20Markup-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/CSS3-Modern%20Styling-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/License-Apache%202.0-blue?style=for-the-badge" />
</p>

---

## 📌 Overview

**CrestWood Realty** is a premium, modern, and responsive real estate web platform crafted to deliver an intuitive property buying, selling, and renting experience. Built with clean semantic HTML5, modern CSS3 styling (featuring glassmorphism, fluid typography, and CSS variables), and vanilla JavaScript, CrestWood Realty combines elegance with high performance across desktops, tablets, and smartphones.

---

## ✨ Key Features

- **🏠 Comprehensive Property Showcase**:
  - Curated listings for luxury modern villas, penthouses, family homes, cottages, and townhouses.
  - Interactive property tags (`For Sale`, `For Rent`, `Featured`).
  - Interactive favorite heart toggle with dynamic state feedback.
  - Granular property metadata: pricing, exact address, bedrooms, bathrooms, and square footage.
  - Smooth **mouse drag-to-scroll** carousel for effortless browsing.

- **🎯 Interactive Contact & Alternative Contact Channels**:
  - **Primary & Alternative Phone Lines**: Direct one-click calling for main office and toll-free lines.
  - **Primary & Alternative Email Inquiries**: Dual email touchpoints for general inquiries and dedicated customer support.
  - **Headquarters Address**: Verified corporate office address in New York, NY.
  - **Interactive CTA section**: Quick-access glassmorphic cards and buttons.

- **💼 End-to-End Real Estate Services**:
  - **Buy A Property**: Tailored guidance through property viewing, price negotiation, and closing.
  - **Sell A Property**: Professional staging, precision market valuation, and marketing campaigns.
  - **Rent A Property**: Short-term and long-term verified rental homes.

- **🌿 World-Class Amenities**:
  - Visual amenity highlights: Covered Parking, Infinity Pools, 24/7 Community Security, Healthcare Facilities, Playgrounds, Fitness Centers, Landscaped Gardens, and Smart Home automation.

- **💬 Client Testimonials**:
  - Verified client reviews and 5-star ratings from buyers, sellers, and renters.

- **📰 Real Estate Insights & Blog**:
  - Industry trends, home buying tips, staging advice, and smart investment guidelines.

- **📱 Responsive & Mobile-First Navigation**:
  - Sticky glassmorphic top header.
  - Animated mobile sidebar drawer menu with backdrop blur.
  - App-style mobile bottom navigation bar for quick thumb access on mobile devices.
  - Smooth scroll anchor linking and scroll-triggered back-to-top button.
  - Intersection Observer scroll reveal animations.

---

## 📞 Contact Details & Alternative Channels

| Detail | Primary Channel | Alternative Channel |
| :--- | :--- | :--- |
| **Brand Name** | **CrestWood Realty** | — |
| **Phone** | [`+1 (212) 555-0190`](tel:+12125550190) *(Main Office)* | [`+1 (800) 555-0199`](tel:+18005550199) *(Toll-Free)* |
| **Email** | [`info@crestwoodrealty.com`](mailto:info@crestwoodrealty.com) | [`support@crestwoodrealty.com`](mailto:support@crestwoodrealty.com) *(Inquiries)* |
| **Corporate Office** | 1250 Crestwood Blvd, Suite 400 | New York, NY 10018 |
| **Office Hours** | Monday – Saturday: 9:00 AM – 8:00 PM | Sunday: 10:00 AM – 4:00 PM |

---

## 🛠️ Tech Stack

- **Markup**: [HTML5](https://developer.mozilla.org/en-US/docs/Web/HTML) — Semantic, accessible page structure
- **Styling**: [CSS3](https://developer.mozilla.org/en-US/docs/Web/CSS) — CSS Variables, Flexbox, Grid, Glassmorphic effects, and fluid breakpoints
- **Interactivity**: [Vanilla JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript) — Zero dependencies; handles sidebar toggle, drag scrolling, favorite saving, and scroll animations
- **Typography**: [Google Fonts](https://fonts.google.com/) — *Poppins* & *Nunito Sans*
- **Icons**: [Ionicons v7](https://ionic.io/ionicons) — High-quality SVG vector icons

---

## 📁 Project Structure

```text
CrestWood-Realty/
├── index.html        # Main single-page application (HTML, CSS, JS)
├── LICENSE           # Apache License 2.0
└── README.md         # Project documentation & website guide
```

---

## 🚀 Getting Started

No build tools, bundlers, or package managers are required. CrestWood Realty runs natively in any modern web browser.

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/CrestWood-Realty.git
cd CrestWood-Realty
```

### 2. Launch the Website
Simply double-click `index.html` to open it in your default browser, or use a local static server:

#### Using Python:
```bash
# Python 3
python -m http.server 8000
```
Then visit `http://localhost:8000` in your web browser.

#### Using Node.js (npx serve):
```bash
npx serve .
```

#### Using VS Code:
Right-click `index.html` and select **"Open with Live Server"**.

---

## 🎨 Customization Guide

### Changing Brand Colors
All colors are configured in the `:root` variables inside `index.html`:
```css
:root {
  --primary: #e8590c;         /* Primary brand accent */
  --primary-dark: #d04a08;    /* Darker hover state */
  --primary-light: #fff4ed;   /* Light tinted backgrounds */
  --secondary: #1b2a4a;       /* Dark heading color */
  --dark: #0f1c35;            /* Dark surface / topbar background */
  ...
}
```

### Updating Contact Details
Contact numbers, email addresses, and location data can be quickly updated in:
1. **Top Bar**: Search for `.topbar-left` in `index.html`.
2. **CTA & Contact Section**: Search for `#contact` in `index.html`.
3. **Footer**: Search for `.footer-contact` in `index.html`.

---

## 📄 License

This project is licensed under the **Apache License 2.0** — see the [LICENSE](LICENSE) file for details.

---

<p align="center">
  &copy; 2026 <strong>CrestWood Realty</strong>. All rights reserved.
</p>
