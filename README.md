# PowerPlay – Sports Equipment E-Commerce Web Application

## Overview
PowerPlay is a full-stack sports equipment e-commerce web application that allows customers to browse, search, and purchase sports products online, while administrators manage inventory, users, and orders efficiently.

The platform’s most distinctive feature is its **content-based recommendation engine**, built from scratch using **TF-IDF (Term Frequency–Inverse Document Frequency)** and **Cosine Similarity**. Whenever a user views or searches for a product, the system automatically recommends similar products.

The application is developed using:

- Python
- Flask
- MySQL
- HTML
- CSS

The payment system is integrated with the **eSewa Demo API** for digital wallet transactions.

---

# Features

## Customer Features

Users can:

- Register and log in as customers
- Browse products by category
- Search products by name
- View detailed product information
- Receive AI-based recommended similar products
- Add products to cart
- Update product quantities in cart
- Remove products from cart
- Checkout and pay using eSewa
- View order and purchase history

---

## Admin Features

Administrators can:

- Log in using a separate admin account
- Access dashboard analytics including:
  - Total users
  - Total products
  - Recent orders
- Add new products
- Edit existing products
- Delete products
- Manage product categories
- Activate or deactivate user accounts
- View all purchase records

---

# Recommendation System

The recommendation engine uses a **content-based filtering approach**:

- TF-IDF is used to convert product descriptions into numerical vectors.
- Cosine Similarity calculates similarity scores between products.
- The system recommends products with the highest similarity scores.

This helps users discover related sports equipment automatically.

---

# Technology Stack

| Technology | Purpose |
|---|---|
| Python | Backend programming |
| Flask | Web framework |
| MySQL | Database management |
| HTML | Frontend structure |
| CSS | Frontend styling |
