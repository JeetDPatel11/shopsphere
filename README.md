# ShopSphere – E-Commerce Web App

A full stack e-commerce application built with the MERN stack (MongoDB, Express, React, Node.js).

## Tech Stack
- **Frontend:** React.js, HTML5, CSS3
- **Backend:** Node.js, Express.js, REST APIs
- **Database:** MongoDB (Mongoose)
- **Authentication:** JWT (JSON Web Tokens), bcrypt

## Features (Roadmap)
- [ ] User registration and login with JWT authentication
- [ ] Product listing with search and filters
- [ ] Shopping cart
- [ ] Order placement and order history
- [ ] Admin panel to add, edit and delete products
- [ ] Responsive UI

## Project Structure
```
shopsphere/
├── backend/    # Express server, routes, models, controllers
└── frontend/   # React app
```

## Getting Started

### Backend
```bash
cd backend
npm install
cp .env.example .env   # add your MongoDB URI and JWT secret
npm run dev
```
The server runs on `http://localhost:5000`. Health check: `GET /api/health`.

### Frontend
```bash
cd frontend
npm create vite@latest . -- --template react
npm install
npm run dev
```

## Author
Jeet Patel – [GitHub](https://github.com/JeetDPatel11)
