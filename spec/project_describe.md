# System Concept: Inventory Management & Store Catalog

## Core Requirements
- **Product Management:** Add, update, and remove items from the inventory.
- **Stock Status Tracking:** Automatically set product status (`Available`, `Running low`, `Out of stock`).

## Stock Status Rules

- **Available:** Quantity > 5
- **Running Low:** Quantity 1 to 5
- **Out of Stock:** Quantity 0
- **Catalog & Filtering:** View products with simple category and status filtering.
- **Item Fields:** Product name, Price, Quantity in stock, Category
