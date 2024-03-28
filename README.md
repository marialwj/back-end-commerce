# E-Commerce Backend 🛒

This project implements a backend for an e-commerce site using Express.js API to use Sequelize to interact with a MySQL database. This backend allows for managing products, categories, and tags associated with the products.

## Features 🌟

- RESTful API for managing e-commerce entities including products, categories, and tags.
- CRUD operations for each entity, allowing for creation, reading, updating, and deletion of products, categories, and tags.
- Sequelize ORM for database management.
- Secure connection to MySQL database using environment variables.

## Technologies Used 💻

- Node.js
- Express.js
- MySQL
- Sequelize ORM
- dotenv for environment variables management

## Getting Started 🚀

### Prerequisites

- Node.js
- MySQL
- npm (Node Package Manager)

### Installation

1. Clone the repository:

```bash
git clone https://github.com/marialwj/back-end-commerce
```

2. 
```bash
npm install
```
3. 
```bash
npm run seed
```
4. 
```bash
node sever.js
```
## Usage 📋
The API can be accessed on http://localhost:3001/api/ and includes the following endpoints:

1. /api/products for products CRUD operations.
2. /api/categories for categories CRUD operations.
/api/tags for tags CRUD operations.
Use a tool like Insomnia or Postman to test the API endpoints.

## Walkthrough
![Walkthrough](ecommerce-walkthrough.mp4)


## License 📄
N/A