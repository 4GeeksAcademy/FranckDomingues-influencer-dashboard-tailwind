# Influencer Analytics Dashboard

A responsive administrative dashboard created with semantic HTML5 and Tailwind CSS v4 for an influencer who needs to consolidate commissions, sales, platform performance, product performance, conversions, and operational details.

## Project Overview

This dashboard helps answer:

- How much commission is being generated.
- Which products generate the most revenue.
- Which platforms provide the strongest performance.
- How audiences progress through the conversion funnel.
- How product sales and commissions compare.

All displayed values are sample data for July 2026.

## Features

- Six KPI cards.
- Platform performance for Instagram, TikTok, and YouTube.
- Product performance for Products A, B, and C.
- Four-stage conversion funnel.
- Semantic operational product table.
- Accessible progress indicators.
- Keyboard-accessible navigation and skip link.
- Mobile-first responsive design.

## Technology

- Semantic HTML5.
- Tailwind CSS v4.
- Tailwind browser CDN: https://cdn.jsdelivr.net/npm/@tailwindcss/browser@4
- Git and GitHub.

This project uses no JavaScript framework, no custom CSS, and no Tailwind v3.

## Responsive Design

Tested viewport ranges:

- Mobile: approximately 375px.
- Tablet: approximately 768px.
- Desktop: approximately 1440px.

Responsive behavior includes:

- KPI cards adapt from one to two to three columns.
- Driver cards adapt responsively.
- Funnel stages adapt from one to two to four columns.
- The operational table scrolls inside its own wrapper on narrow screens.
- The page itself has no horizontal overflow.

## Dashboard Structure

The dashboard is organized into three main blocks:

1. Business Overview.
2. Performance Drivers.
3. Operational Details.

## Run Locally

```bash
python3 -m http.server 3000
```

## Repository

The source code is available in the official 4Geeks Academy repository:

`https://github.com/4GeeksAcademy/FranckDomingues-influencer-dashboard-tailwind`

## Author

**Francisco Garcia**

Civil engineer, Msc Mobile Computing and AI Engineering student focused on building clear, responsive, and accessible digital experiences.

Built as part of the **4Geeks Academy AI Engineering program**.

## Academic Context

This project demonstrates the practical application of:

- Semantic HTML5 landmarks and heading hierarchy.
- Tailwind CSS v4 utility classes.
- Mobile-first responsive design.
- Responsive breakpoints for mobile, tablet, and desktop.
- Reusable visual patterns for cards, panels, progress indicators, and tables.
- Accessible navigation, focus states, progress bars, and tabular content.
- Git commits organized by progressive development stages.

The dashboard uses sample business data for educational purposes. Its primary objective is to demonstrate structure, responsive behavior, semantic HTML, and consistent Tailwind CSS implementation.

## Project Status

Completed and ready for evaluation.

The final dashboard includes:

- Six KPI cards.
- Three performance-driver groups.
- One four-stage conversion funnel.
- One semantic operational table.
- Responsive layouts tested at approximately 375px, 768px, and 1440px.
- Keyboard navigation and accessibility improvements.
