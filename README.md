# Pricing Comparison Table

A responsive pricing comparison table built with semantic HTML5 and modern CSS, based on the [roadmap.sh Pricing Comparison Table project](https://roadmap.sh/projects/pricing-comparison-table).

## 📋 Project Overview

This project displays three subscription plans (Free, Pro, Business) side by side as pricing cards. Each card highlights the plan's features, price, and a call-to-action button. The "Pro" plan is visually emphasized as the most popular option.

## ✨ Features

- **Responsive layout** — cards stack vertically on mobile and align horizontally on desktop
- **Semantic HTML5** — proper use of `<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`
- **Accessible** — ARIA labels, sufficient color contrast, keyboard-navigable buttons
- **Highlighted popular plan** — the Pro plan has a distinct border, badge, and shadow
- **Feature comparison** — storage, projects, and support listed per plan
- **Modern styling** — CSS custom properties (variables), Flexbox/Grid, smooth transitions
- **Call-to-action buttons** — each plan includes a "Get Started" button

## 🛠️ Tech Stack

- **HTML5** — semantic markup
- **CSS3** — Flexbox, Grid, custom properties, media queries
- **No JavaScript required** — pure HTML/CSS solution

## 📁 Project Structure

```
.
├── index.html      # Main HTML file
├── styles.css      # Stylesheet
└── README.md       # Project documentation
```

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/pricing-comparison-table.git
   ```
2. Open `index.html` in your browser.
3. No build step or dependencies required.

## 📱 Responsive Breakpoints

| Breakpoint | Layout |
|------------|--------|
| `< 768px`  | Single column (cards stacked) |
| `≥ 768px`  | Three columns (cards side by side) |

## 🎨 Design Decisions

- **Color palette**: Neutral background with a primary accent color for CTAs and the popular plan.
- **Typography**: System font stack for fast loading and native feel.
- **Spacing**: Consistent 8px-based spacing scale via CSS variables.
- **Popular plan**: Slightly scaled up with a colored border and a "Most Popular" badge.

## ✅ Requirements Checklist

- [x] Three pricing plans displayed
- [x] Each plan shows storage, projects, and support
- [x] Responsive on mobile and desktop
- [x] Popular plan visually highlighted
- [x] CTA button on each plan
- [x] Semantic and accessible HTML
- [x] Footer with copyright notice

## 🔗 Reference

- Project page: https://roadmap.sh/projects/pricing-comparison-table

## 📄 License

MIT