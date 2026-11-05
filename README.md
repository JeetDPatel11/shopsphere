# ShopSphere – E-Commerce Web App

A full stack e-commerce application built with the MERN stack (MongoDB, Express, React, Node.js) where customers can browse products, manage a cart and place orders, while admins manage the product catalog.

## Overview
ShopSphere is designed as an end-to-end online shopping platform. It follows a client-server architecture: a React frontend communicates with a Node.js and Express REST API, which stores data in MongoDB.

## Tech Stack
- **Frontend:** React.js, HTML5, CSS3
- **Backend:** Node.js, Express.js, REST APIs
- **Database:** MongoDB (Mongoose)
- **Authentication:** JWT (JSON Web Tokens), bcrypt password hashing
- **Tools:** Git, GitHub, Postman, VS Code

## Features
- User registration and login with JWT authentication
- Product listing with search and filters
- Product details page
- Shopping cart (add, remove and update quantity)
- Order placement and order history
- Admin panel to add, edit and delete products
- Protected routes for logged-in users and admins
- Responsive user interface

## User Roles
- **Customer:** browse products, manage cart, place orders, view order history
- **Admin:** manage products and view all orders

## Database Design
- **users** – name, email, hashed password, role
- **products** – name, description, price, category, image, stock
- **orders** – user, ordered items, total amount, status, date

## API Endpoints (Planned)
| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | /api/auth/register | Register a new user |
| POST | /api/auth/login | Login and receive a JWT |
| GET | /api/products | Get all products (search and filters) |
| GET | /api/products/:id | Get a single product |
| POST | /api/products | Add a product (admin) |
| PUT | /api/products/:id | Update a product (admin) |
| DELETE | /api/products/:id | Delete a product (admin) |
| POST | /api/orders | Place an order |
| GET | /api/orders/my | Get the logged-in user's orders |

## Application Flow
1. A user registers or logs in and receives a JWT.
2. The user browses and searches products.
3. Selected products are added to the cart.
4. The user places an order from the cart.
5. The admin manages products and reviews orders.

## Future Enhancements
- Online payment integration
- Product reviews and ratings
- Wishlist
- Email notifications for orders

## Author
Jeet Patel – [GitHub](https://github.com/JeetDPatel11)
