# e-plantShopping

**Paradise Nursery** is an online plant shop built with React and Redux Toolkit. This repository, `e-plantShopping`, is the final project for the IBM front-end development course.

## Features

- **Landing page:** background image, company name, an About Us section, and a **Get Started** button that opens the product listing.
- **Product listing:** plants grouped into categories (Air Purifying, Aromatic Fragrant, Insect Repellent, Medicinal, Low Maintenance). Each plant card shows a thumbnail, name, description, price, and an **Add to Cart** button. After a plant is added, its button is disabled and reads "Added to Cart".
- **Navbar:** links to Home, Plants, and Cart. The cart icon shows the total number of items in the cart and updates as the cart changes.
- **Shopping cart:** shows the total cart amount, the total number of plants, and a card per plant type with its thumbnail, name, unit price, subtotal, +/- quantity buttons, and a **Delete** button. It also has **Continue Shopping** and **Checkout** (coming soon) buttons.

## Tech Stack

- React 18 + Vite
- Redux Toolkit / React Redux (`CartSlice.jsx`, `store.js`)

## Running Locally

```bash
npm install
npm run dev
```

## Deployment

```bash
npm run deploy
```

This builds the app and publishes the `dist` folder to the `gh-pages` branch.
