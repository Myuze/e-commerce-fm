# E-commerce Backend
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Description:

---
An E-commerce Backend created in Node.js with Express and SQL Database ready to support online stores by providing the ability to  track products with category tags.

## Table of Contents:

---
1. [Installation Instructions](#installation-instructions)
2. [Usage](#usage)
3. [Contribute](#contribute)
4. [Licenses](#licenses)
5. [Questions](#questions)

## Installation Instructions:

---
### Must have MySQL installed.

1. Clone the Git repository `e-commerce-fm`.
2. Run `npm install`
3. Start MySQL server, then in `MySQL` add the schema by running `SOURCE db/schema.sql`
4. Start the server with: `npm start`.
5. Seed the DB with `npm run seed`.

## Usage:

---
Update the DB with the following endpoints.
- Products
  - View All Products: Method - GET http://localhost:3001/api/products
  - View Product by ID: Method - GET http://localhost:3001/api/products/:id
  - Add Product: Method - POST http://localhost:3001/api/products

      ```
      {
        "product_name": "<product_name>",
        "price": 200.99,
        "stock": 3,
        "category_id": 4,
        "tagIds": [1, 2, 3, 4]
      }
      ```
  - Update Product: Method - PUT http://localhost:3001/api/products/:id
    - Same format as above
  - Delete Product: Method - DELETE http://localhost:3001/api/products/:id

- Categories
  - View All Categories: Method - GET http://localhost:3001/api/categories
  - View Categories by ID: Method - GET http://localhost:3001/api/categories/:id
  - Add Categories: Method - POST http://localhost:3001/api/categories

      ```
      {
	      "category_name": "<category_name>"
      }
      ```
  - Update Categories: Method - PUT http://localhost:3001/api/tags/:id
    - Same format as above
  - Delete Categories: Method - DELETE http://localhost:3001/api/tags/:id

- Tags
  - View All Tags: Method - GET http://localhost:3001/api/tags
  - View Tags by ID: Method - GET http://localhost:3001/api/tags/:id
  - Add Tags: Method - POST http://localhost:3001/api/tags

      ```
      {
	      "tag_name": "<tag_name>"
      }
      ```
  - Update Tags: Method - PUT http://localhost:3001/api/tags/:id
    - Same format as above
  - Delete Tags: Method - DELETE http://localhost:3001/api/tags/:id

## Contribute:

---
- Email me at the email below.

## Licenses:

---
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
**MIT License**
Copyright &#169; 2021

## Questions:

---

### What is your Github username?

[Myuze](https://github.com/Myuze)

### If you have any other questions, you can reach me at:

[flmeneses.dev@gmail.com](mailto:flmeneses.dev@gmail.com)
