# Products API Test Cases

## GET All Products
- Check status code 200
- Response time < 500ms
- Response is an array
- Every product has required fields:
  - id (number)
  - title (string, not empty)
  - price (number > 0)
  - category (string, not empty)
  - image (string, contains 'http')
  - rating (object with rate (0–5) and count)
- At least one product costs less than $20

## GET Product by ID
- Check status code 200
- Validate product has:
  - id
  - title
  - price
  - description
