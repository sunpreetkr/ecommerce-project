# SwiftCart - React E-Commerce Application

## Overview

SwiftCart is a modern eCommerce web application built with React, Vite, React Router, Axios, and Vitest. The application allows users to browse products, add items to a shopping cart, manage quantities, select delivery options, place orders, and review previous purchases.

The project demonstrates modern frontend development concepts including component-based architecture, API integration, state management, automated testing, routing, and cloud deployment on AWS.

---
<img width="1419" height="681" alt="Screenshot 2026-05-31 at 9 23 22 pm" src="https://github.com/user-attachments/assets/3e5356e7-6aab-4a70-b71f-e10b621aaee3" />
<img width="1364" height="672" alt="Screenshot 2026-05-31 at 9 24 13 pm" src="https://github.com/user-attachments/assets/de57e7e7-804d-41b5-818e-cbc3866254e7" />
<img width="1413" height="679" alt="Screenshot 2026-05-31 at 9 23 41 pm" src="https://github.com/user-attachments/assets/0f63a9fb-a9d8-4ddf-a9f4-0ccb0a1f72f5" />

## Features

### Product Catalog

* Browse products in a responsive grid layout
* View product images, ratings, prices, and descriptions
* Search products using the search bar
* Select quantity before adding products to cart

### Shopping Cart

* Add products to cart
* Update product quantities
* Remove products from cart
* Real-time cart updates

### Checkout

* Review cart items
* Select delivery options
* View shipping costs
* View payment summary
* Calculate taxes and order totals

### Orders

* View order history
* Review previous purchases
* Reorder products with a single click
* Track package navigation

### Automated Testing

* Unit testing with Vitest
* Component testing using React Testing Library
* Mock API testing

### Deployment

* Frontend deployed to AWS
* Production-ready React build using Vite

---

## Tech Stack

### Frontend

* React
* Vite
* React Router
* Axios
* Day.js

### Testing

* Vitest
* React Testing Library

### Cloud & Deployment

* AWS

### Version Control

* Git
* GitHub

---

## Project Structure

src/

├── components/

│ └── Header

├── pages/

│ ├── home/

│ ├── checkout/

│ └── orders/

├── utils/

│ └── money.js

├── tests/

└── App.jsx

---

## Key Concepts Demonstrated

### React Router

* Client-side routing
* Dynamic navigation
* URL search parameters

### Data Fetching

* Axios GET requests
* API integration
* Asynchronous operations

### Data Mutation

* Create, Update, Delete operations
* Cart management
* Order creation

### State Management

* useState
* useEffect
* Component communication through props

### Testing

* Unit tests
* Component tests
* Mocking API responses

### Deployment

* Production build generation
* AWS deployment workflow

---

## Learning Outcomes

This project covers:

1. React Fundamentals
2. React Components
3. React Hooks
4. React Router
5. API Integration
6. Data Fetching
7. Data Mutation
8. Automated Testing with Vitest
9. Git & GitHub Workflow
10. AWS Deployment

---

## Installation

Clone the repository:

```bash
git clone <repository-url>
```

Install dependencies:

```bash
npm install
```

Run development server:

```bash
npm run dev
```

Run tests:

```bash
npm run test
```



## Future Improvements

* User Authentication
* Payment Gateway Integration
* Product Categories
* Wishlist Functionality
* Order Tracking API
* Admin Dashboard
* Product Reviews
* Inventory Management

