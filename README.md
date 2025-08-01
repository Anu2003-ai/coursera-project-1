# Plantify - Houseplant E-Commerce React App

Plantify is a simple React and Redux based houseplant e-commerce application.  
It allows users to browse a selection of houseplants, add plants to their shopping cart, and manage cart contents with increment, decrement, and delete features.

---

## Features

- **Landing Page**
  - Displays a beautiful background image.
  - Shows company name and a brief description.
  - "Get Started" button navigates to the product listing.

- **Product Listing Page**
  - Displays 6 unique houseplants grouped into at least 3 categories.
  - Each plant shows a thumbnail image, name, and price.
  - "Add to Cart" button adds the plant to the cart, disables itself after selection, and increments the cart icon count.

- **Header**
  - Persistent on product listing and shopping cart pages.
  - Shows navigation buttons to Product Listing and Shopping Cart.
  - Displays a shopping cart icon with the total number of items.

- **Shopping Cart Page**
  - Displays all plants added to the cart with thumbnails, names, unit prices, and quantities.
  - Users can increase or decrease quantity per plant.
  - Delete button to remove plants from the cart.
  - Shows total number of plants and total cost.
  - Checkout button (currently displays “Coming Soon”).
  - Continue Shopping button navigates back to the product listing.

---

## Tech Stack

- React (functional components and hooks)
- Redux for state management
- CSS inline styles for simple styling

---

## Installation and Running Locally

1. Clone the repository:
   npm install
   npm start
npm run build

   git clone https://github.com/yourusername/yourrepo.git
   cd yourrepo
