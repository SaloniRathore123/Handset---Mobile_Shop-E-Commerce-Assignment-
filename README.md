# Handset – Mobile Shop E-Commerce

A clean, single-page mobile/handset e-commerce storefront built with **HTML5, Bootstrap 5.3.3, jQuery and vanilla JavaScript**. Browse handsets, filter by price, add to cart, and place an order with cash-on-delivery — no backend or build step required. Just open `index.html` in a browser.

## Live demo

Open `index.html` directly in any modern browser. The app is entirely client-side (cart and last order persist in `localStorage`).

## Features

- **Product catalog** — 6 handsets from Apple, Samsung and OPPO with SKUs, prices and descriptions
- **Featured section** — highlighted phones on the home page
- **Price filter + sorting** — max-price slider and ascending/descending sort
- **Shopping cart** — add items, adjust quantities, live subtotal/delivery/total
- **Free delivery** on orders above Rs. 4,00,000 (otherwise Rs. 300)
- **Checkout form** — name, phone, address, postal code, country and payment method (cash on delivery)
- **Order confirmation** — order summary modal with order ID, date, items and totals
- **Responsive design** — Bootstrap grid, works on mobile and desktop
- **Client-side persistence** — cart and last order saved via `localStorage`

## Products

| # | Product | SKU | Price |
|---|---------|-----|-------|
| 1 | OPPO A-Series, Purple | HS-OPP-001 | Rs. 57,000 |
| 2 | Samsung Galaxy S, Mint (featured) | HS-SAM-002 | Rs. 2,49,999 |
| 3 | iPhone 13, Midnight | HS-APL-003 | Rs. 1,67,999 |
| 4 | iPhone 14, Starlight (featured) | HS-APL-004 | Rs. 1,95,999 |
| 5 | iPhone Pro, Black Titanium (featured) | HS-APL-005 | Rs. 3,35,999 |
| 6 | iPhone Pro, Natural Titanium | HS-APL-006 | Rs. 3,35,999 |

## Project structure

```
Handset---Mobile_Shop-E-Commerce-Assignment-/
├── index.html        # Single-page storefront (HTML, CSS, JS)
├── images/           # Product photos
│   ├── 2-2.jpg
│   ├── 33.jpg
│   ├── Black-1.jpg
│   ├── iphone-13-1.jpg
│   ├── iphone-14.jpg
│   └── natural.jpg
└── README.md
```

## Tech stack

- HTML5 / CSS3 (custom variables + Bootstrap 5.3.3)
- JavaScript (ES6) + jQuery
- Bootstrap Icons / Bootstrap components (navbar, cards, modals, forms, toasts)
- `localStorage` for cart & last-order persistence

## How to run

1. Clone or download this repository.
2. Open `index.html` in your browser.
3. Browse products → add to cart → checkout → confirm order.

No installation, npm, or server is needed.

## License

This project was created as a mobile-shop e-commerce assignment.

## Author

**Saloni Rathore** — SaloniRathore123  
salonirathore164@gmail.com  
