# E-Commerce Web Application

## 📌 Overview
This is a full-stack e-commerce web application built with modern web technologies. The application allows users to browse products, add them to the cart, and proceed to checkout. It features user authentication, product management, and order processing.

## 🚀 Tech Stack

### Frontend:
- HTML, CSS, Tailwind CSS, Bootstrap
- JavaScript, React
- react-router-dom
- react-icons
- reduxjs/toolkit, react-redux
- react-toastify

### Backend:
- Node.js, Express.js
- MongoDB Atlas, Mongoose
- dotenv, nodemon, cors
- bcryptjs (for password hashing)
- jsonwebtoken (JWT authentication)
- cookie-parser
- moment.js

## 🎯 Features
- User authentication (register, login, logout)
- Secure password hashing using bcryptjs
- JWT-based authentication and authorization
- Product listing and search functionality
- Shopping cart management
- Order processing and checkout
- Redux state management for efficient data flow
- Responsive UI with Tailwind CSS and Bootstrap
- Notifications using react-toastify

## 🏗️ Installation and Setup

### 1️⃣ Clone the Repository
```sh
git clone https://github.com/yourusername/ecommerce-web-app.git
cd ecommerce-web-app
```

### 2️⃣ Install Dependencies
#### Install Frontend Dependencies
```sh
cd client
npm install
```

#### Install Backend Dependencies
```sh
cd server
npm install
```

### 3️⃣ Set Up Environment Variables
Create a `.env` file in the root directory of the backend (`server/`) and configure the following:
```env
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
PORT=5000
```

### 4️⃣ Run the Application
#### Start Backend Server
```sh
cd server
npm start
```

#### Start Frontend Development Server
```sh
cd client
npm start
```

## 📸 Screenshots
_Add screenshots of the application here_

## 🛠️ Future Enhancements
- Implement payment gateway integration
- Add order tracking functionality
- Enhance UI/UX design
- Optimize performance

## 🤝 Contributing
Contributions are welcome! If you'd like to contribute, please fork the repository and submit a pull request.

Feel free to customize it further based on your project specifics!
