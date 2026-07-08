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
