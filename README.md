# Amazon Clone

## Overview

Amazon Clone is a full-stack web application that replicates the core functionalities of the Amazon e-commerce platform. This project was developed to understand and implement essential web development concepts, including front-end design, back-end logic, database management, and user authentication.

## Features

- *User Authentication*: Sign up, login, and manage user accounts securely.
- *Product Browsing*: View a list of products with details such as price, description, and images.
- *Search Functionality*: Search for products by name or category.
- *Shopping Cart*: Add, remove, and manage items in a shopping cart.
- *Order Management*: Place orders and view order history.
- *Responsive Design*: Optimized for both desktop and mobile devices.

## Technologies Used

- *Front-End*:
  - HTML5, CSS3, JavaScript
  - React.js (for building the user interface)
  - Bootstrap (for responsive design)

- *Back-End*:
  - Node.js and Express.js (for server-side logic)
  - MongoDB (for database management)
  - JWT (JSON Web Token) for user authentication
  - RESTful APIs (for communication between front-end and back-end)

- *Deployment*:
  - Heroku or AWS (for hosting the application)
  - GitHub (for version control)

## Installation

### Prerequisites
- Node.js and npm installed
- MongoDB installed locally or using a cloud service like MongoDB Atlas

### Setup Instructions
1. *Clone the Repository*:

       git clone https://github.com/gautami2003/Amazon_Clone.git
       cd amazon-clone


2. *Install Dependencies*:
   
       npm install


3. *Set Up Environment Variables*:
   - Create a `.env` file in the root directory.
   - Add the following environment variables:

         MONGODB_URI=your-mongodb-connection-string
         JWT_SECRET=your-jwt-secret-key
   
4. *Run the Application*:
  
       npm start

   - The application will be running on `http://localhost:3000`.

## Usage

- *Home Page*: View available products and navigate through categories.
- *Product Details*: Click on a product to view more details.
- *Add to Cart*: Add products to your shopping cart and manage quantities.
- *Checkout*: Proceed to checkout and place an order.
- *User Account*: Sign up or log in to manage your orders and account details.

## Contributing

Contributions are welcome! Please fork this repository and submit a pull request for any features, enhancements, or bug fixes.

## Acknowledgements

- Inspired by Amazon's e-commerce platform.
- Thanks to the open-source community for providing tools and libraries used in this project.
