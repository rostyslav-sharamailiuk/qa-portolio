# Sample API Tests

## 1. GET /products
**Request:** GET https://example.com/api/products  
**Expected Result:** Status 200, list of products in JSON  

## 2. POST /login
**Request:** POST https://example.com/api/login  
**Body:** { "email": "test@example.com", "password": "password123" }  
**Expected Result:** Status 200, token returned  

## 3. POST /checkout
**Request:** POST https://example.com/api/checkout  
**Body:** { "cart": [...], "paymentMethod": "credit_card" }  
**Expected Result:** Status 201, order confirmation
