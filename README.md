# La Croûte Dorée — Bakery Website

A fully functional bakery website built as a demo integration for [Tracklyt](https://github.com/prekshaparekh/tracklyt).

## Features

- **16 products** across 4 categories — Breads, Pastries, Desserts, and Drinks
- **Shopping cart** with add/remove, quantity adjustment, and total calculation
- **Checkout modal** with customer form (name, email, phone, notes)
- **Contact form** for customer inquiries
- **Responsive design** with scroll animations, sticky navbar, and category tabs
- **Tracklyt integration** — all orders and messages are sent to the Tracklyt API and appear in the dashboard

## How It Works

Every form submission on this site sends data to the Tracklyt REST API:

- **Place an order** → sends a `bakery_order` payload with customer details, item breakdown, and total
- **Submit contact form** → sends a `contact_message` payload with email and message

All submissions are visible in the [Tracklyt dashboard](https://github.com/prekshaparekh/tracklyt) with charts, filters, and detailed views.

## Setup

1. Clone this repo
2. Open `index.html` in a text editor
3. Find `const TRACKLYT_API_KEY = '...'` and paste your Tracklyt project API key
4. Update `const TRACKLYT_URL = '...'` to point to your Tracklyt server
5. Open `index.html` in a browser or use Live Server

## Tech Stack

- HTML, CSS, JavaScript (vanilla — no frameworks)
- Google Fonts (Playfair Display, Inter)
- Tracklyt REST API for data collection

## Screenshots

| Home | Cart | Dashboard |
|------|------|-----------|
| Browse products by category | Review items before checkout | View orders in Tracklyt |

---

*Powered by [Tracklyt](https://github.com/prekshaparekh/tracklyt)*
