
# KenzieBurguer — Restaurant Shopping Cart

An educational React application featuring a product catalog, search functionality, and interactive shopping cart. Developed during my Full Stack Web Development training at **Kenzie Academy Brasil**.

## Current demo status (11 October 2026)

In a manual visit to the hosted page at [hamburgueria-kenzie-pink.vercel.app](https://hamburgueria-kenzie-pink.vercel.app/), the interface loaded but no products appeared and the shopping cart was empty. The hosted page is **not a working shopping-cart demo** in this observed state. The cause has not been confirmed.

## Overview

KenzieBurguer simulates a restaurant ordering interface where users can browse products, search the menu, and manage items in a shopping cart.

The project demonstrates React component development, state management, API integration, and browser storage.

## Features

- Browse products retrieved from an external API.
- Search products by name or category.
- Add products to the shopping cart.
- Remove individual items from the cart.
- Calculate the total cart value.
- Store cart information in localStorage.
- Display notifications for user interactions.

## Technologies

- React 18
- JavaScript
- Vite
- Axios
- Styled Components
- React Toastify
- CSS

## Getting Started

Clone the repository and install dependencies:

```bash
npm install
npm run dev
```

Open the local URL displayed by Vite.

## API Integration

The application retrieves product information from an external API configured in `src/services/api.js`.

The original API endpoint is:

`https://hamburgueria-kenzie-json-serve.herokuapp.com/products`

**Important:** The product API's current availability has not been verified independently. The empty catalog seen on 11 October 2026 may relate to this legacy integration, but no root cause has been established or code fix attempted.

## Technical Highlights

- Reusable React components.
- State management using React Hooks.
- Dynamic product filtering.
- HTTP requests with Axios.
- Cart persistence using localStorage.
- Conditional rendering and user notifications.

## Project Scope

This project was developed for educational purposes. It demonstrates front-end shopping cart functionality and does not include a complete purchasing or payment system.

The application has not been independently validated for production use.

## Connect

- [LinkedIn](https://www.linkedin.com/in/pedro-henrique-barros-nascimento-2bb684251/)
- [GitHub Profile](https://github.com/pedrohenriquebarrosn)
