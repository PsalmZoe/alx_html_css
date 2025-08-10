# 🎧 Headphones Landing Page

A fully responsive landing page implemented from scratch using only **HTML** and **CSS**, without any external libraries or frameworks.  
The design replicates the provided mockups exactly for **desktop**, **tablet**, and **mobile** screens.

---

## 📌 Features

- Pixel-perfect match to the provided design files (desktop, tablet, mobile)
- Responsive layout:
  - **Desktop view** for screens above 1024px
  - **Tablet view** for screens between 481px and 1024px
  - **Mobile view** for screens 480px or less
- Clean and semantic HTML for better accessibility
- CSS-only implementation (no JavaScript)
- Hover and active states for buttons and links
- Max content width of **1000px** centered on the page
- Fonts: [Source Sans Pro](https://fonts.google.com/specimen/Source+Sans+Pro) and **Spin-Cycle-OT**

---

## 🖼 Preview

**Desktop**  
![Desktop preview](01_headphones_desktop@2x.png)

**Tablet**  
![Tablet preview](01_headphones_tablet@2x.png)

**Mobile**  
![Mobile preview](01_headphones_mobile@2x.png)

---

## 🎯 Requirements

- **No external CSS frameworks** (e.g., Bootstrap not allowed)
- **No JavaScript**
- Hover/active styles:
  - Links: `color: #FF6565`
  - Buttons: `opacity: 0.9`
- Fonts provided or linked via Google Fonts if unavailable locally
- Content width max: **1000px**

---

## 🛠 Implementation Notes

- **Flexbox** and **CSS Grid** were used for layout
- Media queries ensure the correct design on all screen sizes
- All colors, font sizes, and spacing match the design file (minor float values rounded)
- Accessibility tags (`alt`, `aria-label`) applied to all interactive and image elements

---

## 📱 Responsive Behavior

| Screen size      | Layout behavior |
|------------------|-----------------|
| ≥ 1025px         | Desktop layout  |
| 481px – 1024px   | Tablet layout   |
| ≤ 480px          | Mobile layout   |

---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/alx_html_css.git
   cd alx_html_css/headphones


