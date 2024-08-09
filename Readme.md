# Product Management System

A simple CRUD(Create, Read, Update, Delete) web application to manage products. This system allows you to add, view, update, and delete products, calculate total prices with taxes, and search for products by title or category. The data is stored in the browser's local storage.

## Features

- **Add Products**: Input product details like title, price, taxes, ads, discount, count, and category.
- **Calculate Total**: Automatically calculates the total price including taxes and other costs.
- **View Products**: Display a list of all products with options to update or delete them.
- **Update Products**: Modify the details of an existing product.
- **Delete Products**: Remove a single product or delete all products at once.
- **Search Products**: Search for products by title or category.
- **Local Storage**: Data is stored locally in the browser, so it persists even after refreshing the page.

## Structure

### HTML

- **`index.html`**: The main structure of the application, including the input fields for adding products, a table to display products, and search functionality.

### CSS

- **`style.css`**: The stylesheet used to style the application. It provides a dark theme with a red accent color for buttons and total display.

### JavaScript

- **`script.js`**: Contains all the logic for managing products:
  - **Get Total**: Calculates the total price.
  - **Create/Update Product**: Handles the creation and updating of products in local storage.
  - **Clear Data**: Resets the input fields after adding or updating a product.
  - **Show Data**: Displays the list of products.
  - **Delete Product(s)**: Deletes a specific product or all products.
  - **Search Product**: Allows searching for products by title or category.

## Installation

No installation is required for this project. Simply clone the repository or download the files and open the `index.html` file in a web browser.

## Usage

1. **Adding a Product**:
   - Fill in the required fields: title, price, taxes, ads, discount, count, and category.
   - The total price will be automatically calculated.
   - Click the "Create" button to add the product.

2. **Viewing Products**:
   - All added products will be displayed in the table below the input fields.
   - Each product entry will have an "Update" button to modify its details and a "Delete" button to remove it.

3. **Updating a Product**:
   - Click the "Update" button next to the product you wish to modify.
   - The product's details will be filled in the input fields.
   - Modify the details and click the "Update" button to save changes.

4. **Deleting Products**:
   - Click the "Delete" button next to a product to remove it.
   - Use the "Delete All" button to clear all products from the list.

5. **Searching for Products**:
   - Use the search input to find products by title or category.
   - Toggle between "Search by Title" and "Search by Category" to switch search modes.

## Compatibility

- This project is compatible with modern web browsers such as Chrome, Firefox, Safari, and Edge.


Watch a video demo of the Product Management System:

## Video Demonstration

[Watch the CRUD Video](https://github.com/Shahd-Elmnyar/CRUD/raw/main/assets/cruds%20.mp4)

