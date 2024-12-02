# Filterable Product Table

This project is a practical example of how to apply fundamental React concepts to build an interactive and well-structured application. The project consists of a **filterable product table** that allows users to search for products, filter products in stock, and view product categories clearly.

## Overview

The main goal of this project is to demonstrate how to structure a React app by breaking down the UI into independent, reusable components and managing state effectively to create an interactive user experience.

### Features

- **Product Search**: An input field that allows users to type and filter products by name.
- **In-Stock Filter**: A checkbox that, when checked, displays only products that are in stock.
- **Category Display**: Products are grouped and displayed by category, with a header identifying each group.
- **Out-of-Stock Highlighting**: Products not in stock are highlighted with a different color to alert the user.

## Component Structure

The project is composed of the following main components:

1. **FilterableProductTable**
   - The parent component that manages the filter text and `inStockOnly` state.
   - Passes data and event handlers to child components.

2. **SearchBar**
   - A form with an input field for searching and a checkbox for filtering in-stock products.
   - Receives props to display and update the `filterText` and `inStockOnly` states.

3. **ProductTable**
   - A component that receives products and filter preferences and renders the product table.
   - Iterates over the product list and organizes them into category rows and individual product rows.

4. **ProductCategoryRow**
   - Displays the name of a product category with a cell spanning all columns of the table.

5. **ProductRow**
   - Displays a product row with columns for name and price.
   - Applies special styling to the product name if it is out of stock.

## Main React Concepts Applied

- **Componentization**: The UI is broken down into smaller, reusable components like `SearchBar`, `ProductTable`, `ProductCategoryRow`, and `ProductRow`.
- **State and Props**: State is primarily managed in the `FilterableProductTable` component and passed to child components via props.
- **Unidirectional Data Flow**: Data flow is unidirectional, with states passed from parent to child components and updated via callback functions.
- **Conditional Rendering**: Using conditionals to filter products based on search text and the in-stock filter option.
- **Listing and Keys**: Using keys (`key`) to ensure efficient updates to the list of products and categories.

## Technologies Used

- **React**: The main library for building the user interface.
- **JavaScript**: The programming language used for logic and state management.
- **HTML & CSS**: For structuring and styling the UI.

## How to Run the Project

To run the project on your local machine, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/repository-name.git

2. Navigate to the project directory:
  ```bash
  cd repository-name

3. Install the dependencies:
  ```bash
  npm install

4. Start the development server:
  ```bash
  npm start

5. Acess the project in your browser at http://localhost:3000

## Conclusion

This project is an excellent way to understand the logic behind creating interactive React applications and reusable components. It demonstrates how to structure and maintain clean code with a focus on independent components and efficient state management.

Feel free to contribute improvements, suggestions, or fixes!

## My learning

With this project it was easy to see how react can be used to build interfaces with incredible ease, and it was also a great project to learn in a practical way how to use props and useState.