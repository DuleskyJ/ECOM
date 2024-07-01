# E-commerce Back End

## Description
This project is a back end for an e-commerce site using the latest technologies. It includes a functional Express.js API that interacts with a MySQL database using Sequelize ORM.

## Setup Instructions
1. Clone the repository.
2. Install dependencies: `npm install`.
3. Create a `.env` file and add your database credentials:
DB_NAME='ecommerce_db'
DB_USER='your-mysql-username'
DB_PW='your-mysql-password'

4. Create the database schema:

mysql -u root -p
source path/to/schema.sql

## Seed the database:

npm run seed

## Start the server:

npm start

## API Endpoints
GET /api/categories - Get all categories.
GET /api/products - Get all products.
GET /api/tags - Get all tags.
GET /api/categories/:id - Get a single category by ID.
GET /api/products/:id - Get a single product by ID.
GET /api/tags/:id - Get a single tag by ID.
POST /api/categories - Create a new category.
POST /api/products - Create a new product.
POST /api/tags - Create a new tag.
PUT /api/categories/:id - Update a category by ID.
PUT /api/products/:id - Update a product by ID.
PUT /api/tags/:id - Update a tag by ID.
DELETE /api/categories/:id - Delete a category by ID.
DELETE /api/products/:id - Delete a product by ID.
DELETE /api/tags/:id - Delete a tag by ID.

## Walkthrough Video
https://www.loom.com/share/9ee9cae6f8304471bbdb7c41e7d8178d?sid=45a045be-771f-4e08-bd74-33146ef61077

## License
This project is licensed under the MIT License.
