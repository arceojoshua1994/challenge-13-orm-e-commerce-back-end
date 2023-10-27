# E-Commerce Backend

An API backend for e-commerce platforms, built using Node.js, Express, and Sequelize ORM with MySQL.

## Table of Contents

- [Description](#description)
- [Installation](#installation)
- [Usage](#usage)
- [Routes](#routes)
- [License](#license)
- [Contributing](#contributing)
- [Tests](#tests)
- [Questions](#questions)

## Description

This project provides the back end for an e-commerce site. Using the Sequelize ORM, the server interacts with a MySQL database to perform CRUD operations on product, category, and tag data.

## Installation

1. Clone this repository to your local machine.
2. Navigate to the root directory in your terminal.
3. Run `npm install` to install necessary packages.
4. Set up your own `.env` file in the root directory, structured as:

text
DB_NAME='your_database_name'
DB_USER='your_username'
DB_PW='your_password'

- Make sure you have MySQL installed and set up on your machine.
- Start the MySQL command line tool and login. Run the command source db/schema.sql to set up the database.
- Quit the MySQL tool and return to the terminal. Run npm run seed to seed the database.
- Start the server with npm start.

## Usage

Use tools such as Postman or Insomnia Core to test the API routes.

## Routes

GET /api/products - Returns all products with associated category and tag data.
GET /api/products/:id - Returns a single product by ID with associated category and tag data.
POST /api/products - Creates a new product.
PUT /api/products/:id - Updates a product by its ID.
DELETE /api/products/:id - Deletes a product by its ID.
... [Add similar route documentation for Tags and Categories]

## License

This project is licensed under the MIT License.

## Contributing

To contribute to this project, please fork the repository and create a pull request with your changes. All contributions are welcome!

