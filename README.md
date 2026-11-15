# e-plantShopping - Paradise Nursery Shopping Application

A front-end React application (`e-plantShopping`) for an online houseplant nursery. This project allows users to browse a variety of houseplants, organize them by category, and manage a shopping cart before proceeding to checkout.

## Features

**Landing Page**

* Welcoming interface with a custom background image and company overview.
* Direct navigation to the product catalog via a "Get Started" button.

**Product Listing Page**

* Displays a catalog of houseplants organized into three or more distinct categories.
* Each plant card includes a thumbnail image, plant name, and unit price.
* "Add to Cart" functionality that dynamically updates the global cart state and disables the button to prevent duplicate entries.

**Shopping Cart & Navigation**

* Global navigation bar present on both Product and Cart pages, featuring a dynamic shopping cart icon that tracks the total item count.
* Detailed cart view showing each selected plant's thumbnail, name, unit price, and total cost per item type.
* Quantity management controls to increase, decrease, or completely delete items from the cart.
* Calculates and prominently displays the overall total cost and total number of plants in the cart.
* Includes a "Continue Shopping" return link and a placeholder Checkout button.

## Technologies Used

* **React:** For building the user interface and functional components (e.g., `App.jsx`, `ProductList.jsx`, `CartItem.jsx`, `AboutUs.jsx`).
* **Redux:** For global state management of the shopping cart quantities and items (`CartSlice.jsx`).
* **CSS:** For styling, layout, and background image implementation (`App.css`).

## Project Structure

* **Landing Page:** Company introduction and application entry point.
* **Product Listing:** Categorized display of available inventory.
* **Shopping Cart:** Order summary, dynamic total calculations, and item quantity management.
