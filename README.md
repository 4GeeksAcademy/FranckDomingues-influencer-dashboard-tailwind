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
