# Full Stack React Ecommerce Website

This repository contains the code for a simple React ecommerce website with backend implemented using Node.js, Express, and MongoDB. It allows users to sign up, log in, browse products, add products to cart, and perform various other ecommerce functionalities.

## Setup Instructions

1. **Clone the repository:**

   ```bash
   git clone <repository_url>
   ```

2. **Install dependencies:**

   ```bash
   npm install
   ```

3. **Set up environment variables:**

   Create a `.env` file in the root directory and add the following variables:

   ```
   DATABASE_STRING=<your_mongodb_connection_string>
   ```

4. **Run the server:**

   ```bash
   node server.js
   ```

5. **Start the React application:**

   ```bash
   npm start
   ```

## Features

- User authentication (signup, login) with JWT token generation.
- CRUD operations for products.
- Adding/removing products to/from cart.
- Retrieving user's cart data.
- API endpoints for fetching all products, new collections, popular products, etc.

## API Endpoints

- `POST /signup`: Sign up a new user.
- `POST /login`: Log in an existing user and generate JWT token.
- `GET /allproducts`: Fetch all products.
- `GET /newcollections`: Fetch new collections.
- `GET /popularinwomen`: Fetch popular products in women's category.
- `POST /addtocart`: Add a product to user's cart.
- `POST /removefromcart`: Remove a product from user's cart.
- `POST /getcart`: Get user's cart data.
- `POST /addproduct`: Add a new product.
- `POST /removeproduct`: Remove a product.

## Technologies Used

- React
- Node.js
- Express.js
- MongoDB
- JWT for authentication
- Multer for file upload
- CORS for cross-origin resource sharing

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.
