# 🌿 GreenSpace — Responsive Web Layout

**Project 2 | Frontend Development Internship**
**DecodeLabs Industrial Training Kit · Batch 2026**

---

## 📌 About the Project
GreenSpace is a responsive plant shop webpage built as part of the DecodeLabs frontend internship program. The goal of this project was to master **responsive web design** — making a webpage that looks great and works correctly on any screen size, from a small mobile phone to a large desktop monitor.
## 🚀 Live Preview

> Open `index.html` in your browser to view the project locally.

---

## 📁 Project Structure

```
project-2/
├── index.html    — Page structure (HTML)
├── style.css     — All styling and media queries (CSS)
└── README.md     — You are here
```

---

## ✅ Features

- 📱 **Fully Responsive** — adapts to mobile, tablet, and desktop screen sizes
- 🍔 **Hamburger Navigation** — mobile menu using the HTML Popover API (no JavaScript)
- 🛒 **Functional Cart Drawer** — slides in from the right with item management
- 🍞 **Toast Notifications** — confirms when an item is added to cart
- ➕ **Quantity Controls** — increase, decrease, or remove items in the cart
- 💰 **Live Price Total** — cart total updates automatically
- 🎨 **Fluid Typography** — text scales smoothly using CSS `clamp()`
- ♿ **Accessible** — touch targets meet the 44×44px minimum, zoom is not restricted

---

## 🛠️ Built With

- **HTML5** — semantic structure
- **CSS3** — media queries, Flexbox, CSS Grid, custom properties, `clamp()`
- **Vanilla JavaScript** — cart logic, drawer, toast notifications

---

## 📐 Responsive Breakpoints

| Breakpoint | Layout Changes |
|---|---|
| `< 480px` | Single column, stacked nav, toast slides up from bottom |
| `≥ 480px` | Products grid → 2 columns, newsletter form goes side by side |
| `≥ 768px` | Nav becomes horizontal, hero splits into 2 columns, sidebar appears |
| `≥ 1024px` | Products grid → 4 columns, footer → 4 columns |

---

## 💡 Key Concepts Practiced

- **Mobile-First CSS** — base styles target mobile, media queries add complexity upward
- **CSS Grid** — used for the page macro layout (hero, sidebar, footer, product grid)
- **Flexbox** — used for components (nav, buttons, cards, form)
- **Fluid Units** — `%`, `rem`, `vw`, and `clamp()` instead of fixed `px` values
- **CSS Custom Properties** — color palette and spacing defined as variables in `:root`
- **Viewport Meta Tag** — ensures mobile browsers render at the actual device width.

## 📚 Resources Referenced

- [MDN Web Docs](https://developer.mozilla.org) — HTML & CSS reference
- [CSS-Tricks](https://css-tricks.com) — Flexbox and Grid guides
- [CanIUse.com](https://caniuse.com) — browser support checks
- [Google Fonts](https://fonts.google.com) — Playfair Display & Nunito

---

## 👤 Author

**Adegoke**
Frontend Development Intern — DecodeLabs Batch 2026

---

## 📄 License

This project was built for educational purposes as part of an industrial training program.