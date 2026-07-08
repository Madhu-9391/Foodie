# Foodie

# Foodie Frontend

Foodie is a full-stack food ordering platform built using the MERN stack. This frontend application provides a seamless user experience for browsing food items, managing cart operations, secure authentication, checkout, and order tracking.

## Features

* User authentication with JWT and HttpOnly cookies
* Role-Based Access Control (RBAC) for Consumers and Admin
* Browse restaurants and food items
* Add to cart and manage cart operations
* Secure checkout and order placement
* Admin access for managing products and orders
* Responsive UI for desktop and mobile users
* Optimized frontend performance with efficient API integration

## Tech Stack

* React.js
* JavaScript
* HTML
* CSS
* Tailwind CSS (if used)
* Axios
* React Router DOM
* Context API / Redux (if used)
* Vercel (Deployment)

## Project Structure

```bash
frontend/
│
├── public/
├── src/
│   ├── components/
│   ├── pages/
│   ├── context/
│   ├── services/
│   ├── utils/
│   ├── App.js
│   └── main.js
│
├── package.json
└── README.md
```

## Installation

### Clone the repository

```bash
git clone <your-repository-link>
cd frontend
```

### Install dependencies

```bash
npm install
```

### Start development server

```bash
npm run dev
```

## Environment Variables

Create a `.env` file in the root directory and add:

```env
VITE_API_BASE_URL=your_backend_api_url
```

## Deployment

The frontend is deployed using Vercel for fast and reliable hosting.

## Security Features

* JWT-based authentication
* HttpOnly cookies for secure token handling
* Protected routes for authenticated users
* RBAC implementation for Admin and Consumer access control

## Future Improvements

* Payment gateway integration
* Real-time order tracking
* Notification system
* Review and rating system
* Wishlist functionality
# Foodie Backend 

🚀 Backend service for a Swiggy-inspired food ordering platform built using Node.js, Express.js, and MongoDB, handling 1.3K+ monthly requests with secure authentication, cart management, order workflows, and scalable REST API architecture.

---
## Performance Optimizations

- Implemented server-side caching to reduce redundant database queries
- Optimized backend request handling and API workflows
- Modular architecture for scalable application maintenance

## Features

- RESTful API architecture
- JWT-based authentication and authorization
- Role-Based Access Control (RBAC) for Admin and Users
- Restaurant and food item management
- Cart and order management workflows
- Secure authentication using HttpOnly cookies
- MongoDB database integration
- Middleware-based request validation and error handling
- Optimized backend routing and modular architecture
- Server-side caching for improved API performance

---

## Tech Stack

- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT Authentication
- bcrypt.js
- Cookie Parser
- dotenv
- CORS

---

## Project Structure

```bash
backend/
│
├── controllers/
├── routes/
├── models/
├── middleware/
├── config/
├── utils/
├── server.js
└── package.json
```

---

## Installation

### Clone Repository

```bash
git clone <repository-url>
cd backend
```

### Install Dependencies

```bash
npm install
```

### Create Environment Variables

Create a `.env` file in the root directory:

```env
PORT=5000
MONGO_URI=your_mongodb_connection
JWT_SECRET=your_secret_key
CLIENT_URL=your_frontend_url
```

### Run Development Server

```bash
npm run dev
```

---

## API Functionalities

- User registration and login
- Secure authentication and authorization
- Restaurant and menu management
- Cart management APIs
- Order placement and tracking
- Admin management operations
- Protected API routes

---

## Security Features

- JWT authentication
- HttpOnly cookie handling
- Password hashing using bcrypt
- Protected routes middleware
- RBAC implementation for secure access control
---

## Future Improvements

- Payment gateway integration
- Real-time order tracking with Socket.IO
- Notification system
- API rate limiting
- Docker deployment support

---

## Author

Developed by Puppala Madhuvenu 

Backend-focused Full Stack Developer


---

## Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

### Available Scripts

In the project directory, you can run:

#### `npm start`
Runs the app in development mode.  
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

#### `npm test`
Launches the test runner in interactive watch mode.

#### `npm run build`
Builds the app for production to the `build` folder.

#### `npm run eject`
**Note:** This is a one-way operation. Once you eject, you can’t go back!

---

## Learn More
- [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started)  
- [React documentation](https://reactjs.org/)  
