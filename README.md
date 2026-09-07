# Slice, Sip & Swirl ☕🍕🥤

A single-page website for a cafeteria-style café whose entire menu consists of just three things: **coffee, pizza, and milk smoothies**. Instead of trying to look like a full-service restaurant, the design leans into that simplicity — turning "we only make three things" into the site's core visual identity.

## 🌐 Live Preview

Open `slice-sip-swirl.html` directly in any browser — no build step or server required.

## ✨ Features

- **Bold, oversized hero** with a stacked headline that states the concept plainly: *"We make coffee, pizza & smoothies. Nothing else."*
- **Color-coded menu sections** — amber for Coffee, tomato red for Pizza, berry pink for Smoothies — so each category has its own visual identity.
- **Sticky scroll-synced navigation** — the active nav link highlights automatically as you scroll, powered by the `IntersectionObserver` API.
- **Counter-board style menu layout** with sticky category labels beside scrolling item lists.
- **Story section** highlighting the café's philosophy, backed by a few simple stats.
- **Visit section** with hours, address, and a phone number for ordering ahead.
- **Fully responsive** — collapsible mobile navigation menu, adapts down to small screens.
- **Accessible** — visible keyboard focus and respects `prefers-reduced-motion`.

## 🛠️ Built With

- **HTML5** — single self-contained file
- **CSS3** — custom properties, responsive grid/flexbox layouts
- **Vanilla JavaScript** — mobile nav toggle + scroll-based section highlighting
- **Google Fonts** — [Fraunces](https://fonts.google.com/specimen/Fraunces), [Work Sans](https://fonts.google.com/specimen/Work+Sans), [Space Mono](https://fonts.google.com/specimen/Space+Mono)

No frameworks, no build tools, no external JS libraries.

## 📁 Project Structure

```
├── slice-sip-swirl.html   # Complete website (HTML + CSS + JS in one file)
└── README.md              # This file
```

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/slice-sip-swirl.git
   ```
2. Open `slice-sip-swirl.html` in your browser.
3. That's it — no dependencies to install.

## ✏️ Customizing

- **Menu items & prices** — edit the `.item` blocks inside the `Coffee`, `Pizza`, and `Smoothies` sections.
- **Café name & branding** — update the `.brand` element in the header.
- **Address, hours & phone** — edit the `Visit` section near the bottom of the file.
- **Colors** — all accent colors are defined as CSS variables (`--cream`, `--espresso`, `--tomato`, `--butter`, `--bloom`) at the top of the `<style>` block.

## 📄 License

This project is free to use and modify for personal or commercial café/restaurant websites.

---

Made with a simple idea: pick a few things, and make them count.
