# Categories & Products by Category API Test Cases

## GET Categories
- Status code 200
- Response is an array
- At least one category exists

## GET Products by Category
- Status code 200
- All products belong to selected category (uses environment variable `category`)
- At least one product exists
