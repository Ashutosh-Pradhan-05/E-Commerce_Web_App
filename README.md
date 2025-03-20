# E-Commerce Web Application

![project_banner](https://github.com/user-attachments/assets/0c9434a3-154c-433b-be85-2a0dbbb55d08)

## Overview
This comprehensive e-commerce web application is designed to provide a seamless and efficient shopping experience. Built using cutting-edge web technologies, the platform enables users to explore a diverse range of products, manage their shopping carts, and complete secure transactions. Key features include robust user authentication, advanced product management, and an optimized checkout process, ensuring a smooth and secure shopping journey.

## Tech Stack

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

## Features
- User authentication (register, login, logout)
- Secure password hashing using bcryptjs
- JWT-based authentication and authorization
- Product listing and search functionality
- Shopping cart management
- Order processing and checkout
- Redux state management for efficient data flow
- Responsive UI with Tailwind CSS and Bootstrap
- Notifications using react-toastify

## 📸 Project Screenshots

### 1️⃣ Signup Page
The signup page allows users to create an account by providing their profile picture, name, email, password, and confirming their password. Once all fields are filled correctly, the user can click the Signup button to register. The form ensures validation and security, including password encryption before storage.

![project-signup](https://github.com/user-attachments/assets/e47c8a56-eb78-43ca-9e69-b928d8ea4600)



### 2️⃣ Home Page
The home page showcases featured products, categories, and offers a seamless browsing experience for users. It is designed with a responsive UI and allows users to navigate easily through different sections.

![project_banner](https://github.com/user-attachments/assets/fd715ea8-608e-4502-b959-2a0de8af7ce3)



### 3️⃣ Products Page
The product details page provides users with in-depth information about a selected product, including images, descriptions, pricing, and an Add to Cart button.

![project-img1](https://github.com/user-attachments/assets/affd8d58-0ef4-41a3-9bac-7c0a8d3ada0d)



### 4️⃣ Cart Page
The cart page displays all the products a user has added to their shopping cart. Users can update quantities, remove items, and proceed to checkout.

![project-img2](https://github.com/user-attachments/assets/5496c52a-9bcd-4c85-958d-831b1690fd08)



## 🏗️ Installation and Setup

### 1️⃣ Clone the Repository
```sh
git clone https://github.com/Ashutosh-Pradhan-05/E-Commerce_Web_App.git
cd E-Commerce_Web_App
```

### 2️⃣ Install Dependencies
#### Install Frontend Dependencies
```sh
cd frontend
npm install
```

#### Install Backend Dependencies
```sh
cd backend
npm install
```

### 3️⃣ Set Up Environment Variables
Create a `.env` file in the root directory of the backend (`backend/`) and configure the following:
```env
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
PORT=5000
```

### 4️⃣ Run the Application
#### Start Backend Server
```sh
cd backend
npm run dev
```

#### Start Frontend Development Server
```sh
cd frontend
npm start
```

## 🛠️ Future Enhancements
- Implement payment gateway integration
- Add order tracking functionality
- Enhance UI/UX design
- Optimize performance

## Contact

Developed by **Ashutosh Pradhan**.
- **Email**: [contactwithashuind@gmail.com](mailto:contactwithashuind@gmail.com)
- **GitHub**: [https://github.com/Ashutosh-Pradhan-05](https://github.com/Ashutosh-Pradhan-05)
- **LinkedIn**: [https://www.linkedin.com/in/ashutosh-pradhan05](https://www.linkedin.com/in/ashutosh-pradhan05)
- **Twitter**: [https://x.com/Ashutoshtwitind](https://x.com/Ashutoshtwitind)

Feel free to reach out for any queries or support!

**Note**: Ensure MongoDB Atlas is running before starting the server. For any issues or bugs, please open an issue in the repository.
### Thank You to visit my repository.😊
