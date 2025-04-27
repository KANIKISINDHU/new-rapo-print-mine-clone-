E-commerce-Backend-API

Project Overview
This is a Node.js-based backend API for an e-commerce application. It provides a RESTful API for managing products, users, orders, and shopping carts.

Setup Instructions
Prerequisites
  Node.js (version 14.x or higher)
  MongoDB (version 4.x or higher)
  A code editor or IDE of your choice

Step 1: Clone the Repository

bash
git clone https://github.com/KANIKISINDHU/new-rapo-print-mine-clone-.git

Step 2: Install Dependencies

bash
npm install

Step 3: Configure Environment Variables
Create a new file named .env in the root directory of the project and add the following environment variables:

MONGODB_URI=mongodb://localhost:27017/ecommerce
JWT_SECRET=your-secret-key

Replace your-secret-key with a random secret key of your choice.

Step 4: Start the Application

bash
npm start

The application will start on port 3000. You can access the API endpoints using a tool like Postman or cURL.

Features Overview
  Product management: Create, read, update, and delete products
  User management: Create, read, update, and delete users
  Order management: Create, read, update, and delete orders
  Shopping cart management: Add, update, and remove products from the shopping cart
  Authentication and authorization: Use JSON Web Tokens (JWT) to authenticate and authorize users

API Endpoints
Product Endpoints
  GET /products: Retrieve a list of all products
  GET /products/:id: Retrieve a single product by ID
  POST /products: Create a new product
  PUT /products/:id: Update an existing product
  DELETE /products/:id: Delete a product

User Endpoints
  GET /users: Retrieve a list of all users
  GET /users/:id: Retrieve a single user by ID
  POST /users: Create a new user
  PUT /users/:id: Update an existing user
  DELETE /users/:id: Delete a user

Order Endpoints
  GET /orders: Retrieve a list of all orders
  GET /orders/:id: Retrieve a single order by ID
  POST /orders: Create a new order
  PUT /orders/:id: Update an existing order
  DELETE /orders/:id: Delete an order

Shopping Cart Endpoints
  GET /shopping-cart: Retrieve the shopping cart for the current user
  POST /shopping-cart: Add a product to the shopping cart
  PUT /shopping-cart: Update the quantity of a product in the shopping cart
  DELETE /shopping-cart: Remove a product from the shopping cart

Known Issues
  None at this time.

Technologies Used
  Node.js
  Express.js
  MongoDB
  Mongoose
  JSON Web Tokens (JWT)
  Bcrypt.js

  
