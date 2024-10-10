# Ecommerce-NodeJs

This project is an e-commerce platform developed using **Node.js**, **Express.js**, and **MongoDB**, designed to provide full-stack functionality for managing an online store. The application follows the **MVC (Model-View-Controller)** pattern and incorporates user authentication, product management, and shopping cart functionality.

## Features

- **User Authentication**: Secure user registration, login, and password encryption.
- **Product Management**: Add, update, delete products, and categorize them for better organization.
- **View Products**: Users can browse products and their details.
- **Shopping Cart**: Users can add products to a cart, update quantities, and proceed to checkout.

## Technologies Used

- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Templating Engine**: EJS (Embedded JavaScript)
- **Frontend**: HTML, CSS for responsive design
- **Other Libraries**: Mongoose for MongoDB integration, bcrypt for password encryption, dotenv for environment variables.

## Project Structure

- **controllers/**: Contains the business logic for handling requests and managing product data, user sessions, and cart operations.
- **routes/**: Defines routes for user authentication, product management, and cart operations.
- **views/**: Contains the EJS templates for rendering the frontend pages (login, product list, etc.).
- **public/**: Static files like CSS and images.
- **models/**: MongoDB schema definitions for users, products, and cart data.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- **Node.js** and **npm** are installed on your machine.


## Installation

Follow these steps to set up and run the project locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/shohana-howlader/Ecommerce-NodeJs.git

2. Navigate to the project directory:
   ```bash
   cd Ecommerce-NodeJs

3. Install the dependencies:
   ```bash
   npm install

4. Start the application:
   ```bash
   npm start

5. Open your browser and navigate to:
   ```bash
   http://localhost:3000

## Usage
- **Product Management: Admins can add, update, or delete products.
- **Cart Functionality: Users can add products to the cart, view items in the cart, and update quantities.

## Future Enhancements
- **Add database integration (e.g., MongoDB).
- **Implement user authentication.
- **Improve the UI for a more modern look and feel.
## Contributing
- **Contributions are welcome! Feel free to submit pull requests or report issues.

## License
- **This project is licensed under the MIT License.


