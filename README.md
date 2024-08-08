# eCommerce Web Application

A fully functional eCommerce web application built using the MERN (MongoDB, Express, React, Node.js) stack. The application supports user authentication, product management, payment processing, and more.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Environment Variables](#environment-variables)
- [Running the Application](#running-the-application)
- [API Endpoints](#api-endpoints)
- [External APIs Used](#external-apis-used)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [Contributing](#contributing)
- [License](#license)

## Features

- User authentication (Register, Login, Logout) with JWT
- Secure password storage using bcrypt
- Product management (CRUD operations)
- Payment gateway integration with Braintree
- Responsive design using Ant Design
- Real-time data fetching with Axios
- SEO optimization using react-helmet
- Error logging with Morgan

## Technologies Used

- **Frontend**: React, Ant Design, React Icons, Axios, React Helmet
- **Backend**: Node.js, Express, Braintree
- **Database**: MongoDB, Mongoose
- **Authentication**: JWT, bcrypt
- **Tools**: Postman, Nodemon, Concurrently

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/your-repository.git
   cd your-repository

2. **Install dependencies**:
    bash
    Copy code
    npm install
    cd client
    npm install
    cd ..

3. **Set up MongoDB**:
    Ensure MongoDB is installed and running locally or set up MongoDB Atlas.
    Update the MongoDB URI in the .env file.
4. **Environment Variables**
    ##Create a .env file in the root of your project and add the following environment variables:

    PORT=5000
    MONGO_URI=your-mongodb-uri
    JWT_SECRET=your-secret-key
    BRAINTREE_MERCHANT_ID=your-braintree-merchant-id
    BRAINTREE_PUBLIC_KEY=your-braintree-public-key
    BRAINTREE_PRIVATE_KEY=your-braintree-private-key

## Running the Application

To get the application up and running, follow these steps:

1. **Start the server:**

   ```bash
   npm run server

2. **Start the client:**

   ```bash
   npm run client

3. **Run both client and server concurrently:**

   ```bash
   npm run dev
   

## API Endpoints

### Auth
- `POST /api/auth/register`: Register a new user
- `POST /api/auth/login`: Log in an existing user

### Products
- `GET /api/products`: Get all products
- `POST /api/products`: Add a new product
- `PUT /api/products/:id`: Update an existing product
- `DELETE /api/products/:id`: Delete a product

### Payments
- `POST /api/payments`: Process a payment using Braintree

### External APIs Used
- **Braintree**: Payment gateway integration

## Usage
1. Register as a new user or log in as an existing user.
2. Browse products, add them to the cart, and proceed to checkout.
3. Manage products (Add, Edit, Delete) as an admin.
4. Make secure payments using the integrated Braintree payment gateway.

## Screenshots
Add screenshots of your application here to give users a visual overview.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request.

## License
This project is licensed under the MIT License.


