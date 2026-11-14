# Nexus Market (NEXUS-COMMERCE capstone)

A small online store for student desk and study gear, with a seller dashboard.
Built for the GDGoC CUI Wah Beyond Prompting capstone using AI assistance.

## Features
- Storefront: product grid, search, category filter, product page, stock badges
- Cart: add, remove, change quantity, live total
- Simulated checkout (cash on delivery, no card details) with form validation
- Order confirmation, and the order appears in the seller dashboard
- Seller dashboard: order list, status updates, notes, customer list, customer questions, summary numbers
- Empty states, missing-product page, out-of-stock and checkout errors handled
- Works on mobile and desktop, with light and dark mode

## Tech
Plain HTML, CSS and JavaScript in one file (`index.html`). No install needed.

## Run locally
Double-click `index.html`, or run `npx serve` in this folder.

## Data and persistence
All data is fictional demo data. Orders, stock, cart and questions are saved in the
browser's `localStorage`, so they stay on one browser and are not shared between users.
Use "Reset demo data" in the dashboard to start again.

## Deployment
Drag this folder onto https://app.netlify.com/drop, or import the GitHub repo into Vercel.
Add the live link here only after it works. If it fails, write what you tried in `docs/deployment.md`.

## Prompts
See the `prompts/` folder. Only record prompts you really used.


## Live demo
https://courageous-sorbet-188acd.netlify.app

## Screenshots

Home page
![Home](docs/screenshots/home.png)

Cart
![Cart](docs/screenshots/cart.png)

Order confirmation
![Order](docs/screenshots/order.png)

Seller dashboard
![Dashboard](docs/screenshots/dashboard.png)

Mobile view
![Mobile](docs/screenshots/mobile.png)
