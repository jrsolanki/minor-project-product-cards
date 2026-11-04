# Product Cards and Contact Form

A static webpage built as a **minor project for my Pregrad course**. It shows a small product catalogue as styled cards, plus a working-looking contact form — all in plain HTML and CSS, no frameworks and no external images (the product visuals are pure CSS gradients, so the page renders identically offline).

## What's on the page

- **Sticky header** with navigation and a gradient hero section
- **6 product cards**, each with a CSS-gradient visual panel, description, price with a struck-through MRP, a star rating, and an Add to Cart button:
  - Aurora Wireless Headphones — ₹2,999
  - PulseFit Smart Watch — ₹4,499
  - KeyForge Mechanical Keyboard — ₹3,299
  - GlidePro Wireless Mouse — ₹1,299
  - VoltPack 20000mAh Power Bank — ₹1,499
  - EchoBoom 360° Speaker — ₹2,499
- **Cards react to the mouse** — they lift on hover, and the grid is responsive (3 columns → 2 → 1 as the screen narrows)
- **Contact form** — name, email, subject dropdown and message, with focus-glow styling; a small inline script shows a "message noted" confirmation when you submit it
- **Footer** to close the page

## How to run

No install, no build step. Clone the repo and open the page:

```bash
git clone https://github.com/jrsolanki/minor-project-product-cards.git
```

Then open `index.html` in any browser. Keep `style.css` in the same folder — the page loads its styling from it.

## Tech used

- HTML5
- CSS3 (flexbox/grid, gradients, transitions, media queries)
- A few lines of inline JavaScript for the form confirmation

## Files

| File | What it is |
| --- | --- |
| `index.html` | Page structure: header, hero, product grid, contact form, footer |
| `style.css` | All styling: layout, cards, form, responsive breakpoints |

---

Built by Jay Solanki — Computer Engineering student, Government Engineering College Rajkot.
