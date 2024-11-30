# Ecommerce-Website
Ecommerce Project

This project is a practice exercise for developing a full-stack Ecommerce Shopping website using React, Express.js, and MongoDB. It includes features such as product listing, administration for managing product listings, user authentication with login/signup/logout functionality, and the ability for customers to add products to a cart.

Please note that this project is intended for educational purposes and does not include a complete checkout functionality or any real-world payment processing integration.

Technologies Used
Frontend:

React: A JavaScript library for building user interfaces.
HTML/CSS: For structuring and styling the website.
React Router: For routing within the React application.
Backend:

Express.js: A Node.js web application framework for building APIs and handling server-side logic.
MongoDB: A NoSQL database for storing product data and user information.
Features
Product Listing: Displaying available products for customers to browse.
Admin Panel: Allows administrators to manage product listings.
User Authentication: Secure user registration, login, and logout functionality.
Cart Management: Users can add products to a cart for later purchase.
Getting Started
To run this project locally, follow these steps:

Frontend Setup
Creating React App (Frontend folder)

npx create-react-app .
npm install react-router-dom
Start the frontend development server:

npm start
This command will start the frontend server and you can access the frontend at http://localhost:3000.

Backend Setup
Express installation process

npm install express
npm init
npm install jsonwebtoken
Other necessary packages

npm install mongoose
npm install multer
npm install cors
Start the backend server:

node ./index.js
This command will start the backend server, and you can access the backend API at http://localhost:5000.

Admin Setup
Create Vite App (Admin)

npm create vite@latest .
npm install
Start the admin server:

npm run dev
This command will start the admin server.

#Extract assets.zip folder and place it in frontend->src->Components And also place it in admin->src
