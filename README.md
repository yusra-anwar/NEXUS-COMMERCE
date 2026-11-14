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
The live link is in the Live demo section below.
## Prompts
The prompt logs are in the `prompts` folder, one file for each part of the website.


## Live demo
https://courageous-sorbet-188acd.netlify.app

## Screenshots

Home page
![Home](prompts/docs/Screenshot%202026-11-14%20162540.png)

Cart
![Cart](prompts/docs/Screenshot%202026-11-14%20162705.png)

Order confirmation
![Order confirmation](prompts/docs/Screenshot%202026-11-14%20165606.png)

Seller dashboard
![Dashboard](prompts/docs/Screenshot%202026-11-14%20163225.png)

Mobile view
![Mobile](prompts/docs/Screenshot%202026-11-14%20164346.png)
