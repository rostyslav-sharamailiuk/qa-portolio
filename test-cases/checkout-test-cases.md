| ID    | Test Case                          | Steps                                                                   | Expected Result                                     | Status |
|-------|------------------------------------|-------------------------------------------------------------------------|----------------------------------------------------|--------|
| TC001 | Login with valid credentials       | 1. Open login page 2. Enter valid email/password 3. Click login         | User is redirected to dashboard                    | Pass   |
| TC002 | Login with invalid password        | 1. Open login page 2. Enter valid email + wrong password 3. Click login | Error message "Invalid credentials" appears        | Pass   |
| TC003 | Add product to cart                | 1. Open product page 2. Click "Add to cart"                             | Product appears in cart                            | Pass   |
| TC004 | Checkout with valid payment        | 1. Go to cart 2. Click checkout 3. Enter valid payment info 4. Submit   | Payment successful, order confirmation shown       | Pass   |
| TC005 | Checkout with empty cart           | 1. Open checkout page without products in cart                          | Checkout disabled or message "Cart is empty"       | Pass   |
