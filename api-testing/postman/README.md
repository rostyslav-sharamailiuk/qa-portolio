# FakeStore API Testing – Postman

This repository contains **Postman API tests** for the FakeStore e-commerce API.  
The tests cover basic functionality, data validation, and response correctness for products, users, carts, and categories.

## Included Test Cases

- **Products**  
  - GET all products  
  - GET product by ID  
  - Validate required fields (id, title, price, category, image, rating)  
  - Check ratings are between 0–5  
  - Check at least one product costs less than $20

- **Users**  
  - GET all users  
  - POST login (token verification)

- **Cart**  
  - POST create cart  
  - Validate cart creation and products

- **Categories**  
  - GET categories  
  - GET products by category (with environment variable support)

## How to Run Tests

1. Import `postman_collection.json` into Postman.
2. Set up environment variables (optional, e.g., `category` for category tests).  
3. Run individual requests or the full collection with Postman Runner.  
4. View test results in the **Tests tab**.

## Postman Collection

[Open in Postman](https://go.postman.co/collection/52006044-520d1a01-8311-4ca3-9c70-a03a7d0da103?source=collection_link)

---
