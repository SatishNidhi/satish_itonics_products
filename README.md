## Product Types Management

### Overview

The ITONICS Products Module now supports dynamic management of product types. This allows administrators to define various types of products within the system.

### Features

- **CRUD Operations**: Create, read, update, and delete product types.
- **Attributes**: Define attributes for product types including name and status.
- **Integration**: Seamlessly integrate product types with existing product management functionalities.

### Usage

1. **Admin Interface**: Navigate to `Admin > Product Types` in the Drupal admin panel.
2. **Type Listing**: View existing product types and their attributes.
3. **Type Details**: Click on a type to view or modify its details.
4. **CRUD Operations**:
   - **Create**: Click on `Add Product Type` to define a new type.
   - **Update**: Edit type details using the `Edit` option.
   - **Delete**: Remove a type by selecting `Delete` (confirm deletion prompt).

### Dependencies

- **Drupal 7**: Requires Drupal 7 CMS framework.

## Product Categories Management

### Overview

The ITONICS Products Module now includes functionality for managing product categories dynamically. This feature enables administrators to categorize products effectively.

### Features

- **CRUD Operations**: Create, read, update, and delete product categories.
- **Attributes**: Define category attributes like name, product_type, status and hierarchical relationships.
- **Integration**: Link categories with products to organize and classify them within the system.

### Usage

1. **Admin Interface**: Navigate to `Admin > Product Categories` in the Drupal admin panel.
2. **Category Listing**: View existing categories and their attributes.
4. **CRUD Operations**:
   - **Create**: Click on `Add Product Category` to define a new category.
   - **Read**: View category details by selecting a category from the list.
   - **Update**: Modify category details using the `Edit` option.
   - **Delete**: Remove a category by selecting `Delete` (confirm deletion prompt).

### Dependencies

- **Drupal 7**: Requires Drupal 7 CMS framework.
- **Choosen**: Utilizes Choosen for searchable select.


## Features

- **Product Management**: Create, edit, view, and delete products.
- **Attributes**: Manage product attributes including title, image, summary, description, category, type, owner email, and expiry date.
- **UI Enhancements**: Utilizes Drupal's Form API for creating rich user interfaces with textfields, select lists, datepickers, and rich text editing capabilities (TinyMCE).
- **Image Handling**: Integrates Drupal's file upload system and image styles for managing product images.
- **Data Storage**: Stores product information in a dedicated database table (satish_itonics_products).

# ITONICS Products Module

## Overview

The ITONICS Products Module is a custom Drupal 7 module designed to manage product information within the ITONICS platform. This module provides CRUD (Create, Read, Update, Delete) functionalities for products

## Features

- **Product Management**: Create, edit, view, and delete products.
- **Attributes**: Manage product attributes including title, image, summary, description, category, type, owner email, and expiry date.
- **UI Enhancements**: Utilizes Drupal's Form API for creating rich user interfaces with textfields, select lists, radio buttons, datepickers, and rich text editing capabilities (TinyMCE).
- **Image Handling**: Integrates Drupal's file upload system and image styles for managing product images.
- **Data Storage**: Stores product information in a dedicated database table (satish_itonics_products).


## Usage

1. **Admin Interface**: After installation, navigate to the Admin > Products section in the Drupal admin panel.
2. **Product Listing**: View a list of existing products with basic details including title and image.
3. **Product Details**: Click on a product to view detailed information such as summary, description, category, type, owner email, and expiry date.
4. **CRUD Operations**:
   - **Create**: Click on Add Product to create a new product, filling out the required fields.
   - **Read**: View product details by clicking on a product title in the list.
   - **Update**: Edit product details by clicking on Edit next to a product in the list.
   - **Delete**: Remove a product by clicking Delete next to a product in the list (confirm deletion prompt).


## Dependencies

- **Drupal 7**: The module is built on Drupal 7 CMS framework.
- **TinyMCE**: Used for rich text editing capabilities in product
- **Choosen**: Utilizes Choosen for searchable and multiple select.
- **Datepicker**: Utilizes Datepicker for selecting date.




## Support

For any issues, questions, or feedback regarding the ITONICS Products Module, please contact `satish.nidhi123@gmail.com`.
