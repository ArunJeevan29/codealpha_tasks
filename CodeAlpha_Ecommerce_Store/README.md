# Urban Threads

> Premium Streetwear E-commerce Store

Urban Threads is a modern, fully-functional e-commerce platform built with **HTML, CSS, JavaScript, React (Frontend), Node.js, Express, and MongoDB**. It features a custom "Streetwear" aesthetic with a responsive design and full shopping cart functionality.

## Features

- **Modern UI/UX**: Custom dark/streetwear theme with vibrant accents and smooth transitions.
- **Product Catalog**: Dynamic product listing with specific streetwear branding.
- **Shopping Cart**: Full add-to-cart, update quantity, and remove item functionality.
- **User Accounts**: Sign in, Register, and Profile management.
- **Order Management**: Checkout flow, shipping, payment (PayPal integration), and order history.
- **Admin Dashboard**: backend management for products and orders.

## Tech Stack

- **Frontend**: HTML5, CSS3 (Custom), JavaScript (ES6+), Webpack
- **Backend**: Node.js, Express.js
- **Database**: MongoDB (Mongoose)

## How to Run Locally

1.  **Clone the repository**
2.  **Install Root Dependencies**
    ```bash
    npm install --legacy-peer-deps
    ```
3.  **Build Frontend**
    ```bash
    cd frontend
    npm install
    npm run build
    cd ..
    ```
4.  **Setup Environment**
    Create a `.env` file in the root directory:

    ```
    MONGODB_URL=mongodb://localhost/urbanthreads
    JWT_SECRET=somethingsecret
    PAYPAL_CLIENT_ID=sb
    ```

    _Ensure you have MongoDB running locally._

5.  **Run the Server**
    ```bash
    npm start
    ```
6.  **Visit**: [http://localhost:5000](http://localhost:5000)

## License

ISC
