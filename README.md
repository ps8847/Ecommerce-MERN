# MERN E-commerce

This is a MERN (MongoDB, Express.js, React.js, Node.js) stack E-commerce application with features like product listing, product details, cart functionality, user authentication, and payment processing.

# Live Link 
You can access the live version [here](https://ecommerce-mern-woad.vercel.app/auth/login).

## Installation

To run this project locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/ps8847/Ecommerce-MERN.git
    ```
2. Install dependencies:
    
    For backend:
    
    ```bash
    cd server
    npm install
    ```

    For frontend:
    ```bash
    cd client
    npm install
    ```

3. Create .env files:
    
    For backend:Create a .env file in the backend directory with the following fields:

    ```bash
    DB_LINK=
    PAYPAL_MODE=
    PAYPAL_CLIENT_ID=
    PAYPAL_CLIENT_SECRET=
    CLOUDINARY_NAME=
    CLOUDINARY_API_KEY=
    CLOUDINARY_API_SECRET=
    ```

4. Start the development servers:

    For backend:
    ```bash
    cd server
    npm run dev
    ```

    For frontend:
    ```bash
    cd client
    npm run dev
    ```

## Tech Stack

**Frontend:**
React.js,
Redux,
Cloudinary

**Backend:**
Node.js,
Express.js,
MongoDB,
Cloudinary (for image management),
PayPal (for payment processing),

# Features

## User Panel:
User authentication,
Product browsing,
Product details,
Shopping cart,
Checkout and payment processing

## Admin Panel:
Product management (add, edit, delete),
User management,
Order management,


## Contributing
Contributions are welcome! Please feel free to submit a pull request.

## License
This project is licensed under the MIT License - see the LICENSE file for details.