# Full Stack React Ecommerce Website

This repository contains the code for a simple React ecommerce website with backend implemented using Node.js, Express, and MongoDB. It allows users to sign up, log in, browse products, add products to cart, and perform various other ecommerce functionalities.

## Setup Instructions

1. **Clone the repository:**

   ```bash
   git clone https://github.com/bchakradhar20/Full-Stack-React-Ecommerce-Website.git
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
  ![image](https://github.com/user-attachments/assets/934e5e04-1474-495d-9ba4-1cb2bd265f9e)
  ![image](https://github.com/user-attachments/assets/aaf8e5fc-d539-42e9-8534-7d7391e09404)
  ![image](https://github.com/user-attachments/assets/3cf6ff7c-28bc-4034-a969-a7a6abfbbb31)
  ![image](https://github.com/user-attachments/assets/ca26e96b-2b36-4e4f-aede-4658cc3bff10)
  ![image](https://github.com/user-attachments/assets/9c6ab742-47c7-4d16-8273-d3b666306713)
  ![image](https://github.com/user-attachments/assets/a5059b6b-3ed8-44a5-9b71-e8b94fc7f746)
  ![image](https://github.com/user-attachments/assets/e56dca7c-e2e3-4b7f-b7dd-ef2823dbe9d1)
  ![image](https://github.com/user-attachments/assets/dc4cff0d-4242-4439-8842-738cd1d20663)









## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.
