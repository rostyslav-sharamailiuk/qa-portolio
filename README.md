# QA Portfolio – Rostyslav Sharamailiuk

This repository contains my QA portfolio with a focus on **manual testing**, **API testing using Postman**, and **basic frontend knowledge (HTML/CSS/JS)**.  
All examples are based on real e-commerce scenarios.

---

## 1. API Testing (Postman)

**Location:**  
`api-testing/postman/`

### Collections & Environment
- **Postman Collection:**  
  `E-commerce API Testing – FakeStore.postman_collection.json`
- **Postman Environment:**  
  `FakeStoreAPI.postman_environment.json`

### Covered API Scenarios
- **Products**
  - GET All Products
  - GET Product by ID
- **Categories**
  - GET Categories
  - GET Products by Category (using environment variables)
- **Users**
  - GET All Users
  - POST Login (token validation)
- **Cart**
  - POST Create Cart

### What is tested
- Status codes (200 / 201)
- Response time
- Response structure and required fields
- Data validation (price, category, rating, IDs)
- Environment variables usage
- Automated assertions using `pm.test()`

Detailed API test descriptions can be found in:  
`api-testing/postman/test-cases/`

---

## 2. Manual Testing & UX Notes

**Location:**  
`test-cases/`

Manual test cases and UX notes based on **PrestaShop demo e-commerce store**.

### Covered Areas
- Login & Registration
- Product catalog and search
- Filters and sorting
- Cart and checkout process
- General usability and navigation

Includes:
- Positive and negative test cases
- UX observations
- Identified usability issues

---

## 3. Bug Reports

**Location:**  
`bug-reports/`

Sample bug reports written according to standard QA practices:
- Clear title
- Environment details
- Steps to reproduce
- Expected vs actual result
- Severity and priority

---

## 4. Test Plan

**Location:**  
`test-plan/`

Example test plan describing:
- Scope of testing
- Test objectives
- Test types
- Entry and exit criteria
- Risks and assumptions

---

## 5. Skills Demonstrated

- Manual testing of web applications (functional, UI/UX, exploratory)
- API testing using Postman
- Writing simple automated tests in Postman
- Working with environment variables
- Understanding of e-commerce flows (catalog, cart, checkout, payments)
- Basic HTML, CSS, JavaScript knowledge
- Bug reporting and test documentation
- Git & GitHub for version control

---

## Contact

**Email:** rsharamailuk13@gmail.com
