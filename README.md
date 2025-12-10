# MERN E-commerce Website 🛒

![MERN E-commerce](https://img.shields.io/badge/MERN%20E-commerce%20Website-Ready%20to%20Use-brightgreen)

Welcome to the **MERN E-commerce Website** repository! This project serves as a comprehensive tutorial for building an e-commerce application using the MERN stack. It covers essential features such as product management, user authentication, and payment integration. 

[Check out the releases here!](https://github.com/roniepascal/mern-ecommerce-website/releases)

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Folder Structure](#folder-structure)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features

- **Product Management**: Add, edit, and delete products with ease.
- **User Authentication**: Secure user login and registration process.
- **Payment Integration**: Seamless payment processing using PayPal API.
- **Ratings and Reviews**: Users can leave feedback on products.
- **Responsive Design**: Built with Tailwind CSS for a modern look.
- **State Management**: Uses Redux Toolkit for efficient state management.

## Technologies Used

This project leverages a variety of technologies:

- **MERN Stack**: MongoDB, Express.js, React, Node.js
- **Cloudinary**: For image uploads and management.
- **PayPal API**: For handling payments.
- **Redux Toolkit**: For state management in React.
- **Tailwind CSS**: For styling the application.
- **User Reviews**: To enhance product credibility.

## Installation

To get started with the MERN E-commerce Website, follow these steps:

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/roniepascal/mern-ecommerce-website.git
   ```

2. **Navigate to the Project Directory**:

   ```bash
   cd mern-ecommerce-website
   ```

3. **Install Dependencies**:

   For the server:

   ```bash
   cd server
   npm install
   ```

   For the client:

   ```bash
   cd client
   npm install
   ```

4. **Set Up Environment Variables**:

   Create a `.env` file in the server directory and add the necessary environment variables such as MongoDB URI and PayPal Client ID.

5. **Run the Application**:

   Start the server:

   ```bash
   cd server
   npm start
   ```

   Start the client:

   ```bash
   cd client
   npm start
   ```

Visit `http://localhost:3000` to see the application in action!

## Usage

Once the application is running, you can:

- Register a new user account.
- Log in to your account.
- Browse through the product catalog.
- Add products to your cart.
- Proceed to checkout and make payments using PayPal.
- Leave ratings and reviews for products you purchase.



## Folder Structure

Here's a brief overview of the folder structure:

```
mern-ecommerce-website/
├── client/                  # React frontend
│   ├── public/              # Static files
│   ├── src/                 # React components and assets
│   └── package.json         # Client dependencies
└── server/                  # Node.js backend
    ├── config/              # Configuration files
    ├── controllers/         # Request handlers
    ├── models/              # Database models
    ├── routes/              # API routes
    └── package.json         # Server dependencies
```

