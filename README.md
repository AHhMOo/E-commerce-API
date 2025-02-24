E-Commerce Project Documentation
Overview
This project is an e-commerce application created to manage customers, products, and orders. It includes a frontend developed using React and a backend built with Flask. Users can perform CRUD operations on customers and products, as well as place orders through the interface.

Setup and Installation
Prerequisites:
Node.js and npm for managing frontend dependencies.
Python and pip for managing backend dependencies.
Flask for the backend API.
SQLAlchemy for database management.
Bootstrap for styling.
File Structure
Frontend:
App.jsx: Handles routing and navigation.
CustomerList.jsx: Displays a list of customers.
CustomerForm.jsx: A form to create or edit customers.
ProductList.jsx: Displays a list of products.
ProductForm.jsx: A form to create or edit products.
OrderForm.jsx: A form to place orders.
HomePage.jsx: The home page, offering navigation options.
NotFound.jsx: 404 error page for undefined routes.
api.jsx: Contains API call functions.
index.css: Global styling.
Backend:
e_commerce.py: The main application file for Flask.
Components
HomePage
Purpose: Greets the user and provides a "Shop Now" button.
Key Features: Responsive layout, styled with Bootstrap.
CustomerList
Purpose: Displays a list of all customers.
Key Features: Ability to delete customers.
CustomerForm
Purpose: Allows users to create or edit customer details.
Key Features: Form validation, redirects after submission.
ProductList
Purpose: Displays all products.
Key Features: Ability to delete products.
ProductForm
Purpose: Allows users to create or edit product details.
Key Features: Form validation, redirects after submission.
OrderForm
Purpose: Facilitates order placement.
Key Features: Form for selecting customers and products, includes error and success messages.
NotFound
Purpose: Displays a 404 error message for non-existent routes.
Key Features: Option to return to the home page.
API Endpoints
Customers
GET: Retrieve all customers.
POST: Create a new customer.
PUT: Update an existing customer.
DELETE: Delete a customer.
Products
GET: Retrieve all products.
POST: Create a new product.
PUT: Update an existing product.
DELETE: Delete a product.
Orders
POST: Place a new order.
CSS Styling
Global Styles:
Defined in index.css.

Component-Specific Styles:
Each component may have its own specific CSS file for styling.
