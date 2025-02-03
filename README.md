# Products_CRUDS

Products_CRUDS

Project Overview

The Products_CRUDS repository is a machine test project implementing CRUD (Create, Read, Update, Delete) operations for Category and Product Masters. It is developed using Node.js, Angular, and RDBMS with server-side pagination.

Technologies Used

Backend: Node.js, Express.js

Frontend: Angular

Database: Relational Database Management System (RDBMS)

ORM: Sequelize (if used)

Pagination: Server-side implementation for efficient data handling

Features

CRUD operations for Category Master

CRUD operations for Product Master

Server-side pagination for optimized data retrieval

API integration between backend and frontend

Validation and error handling

Installation & Setup

Backend Setup (Node.js)

Clone the repository:

git clone https://github.com/EngineerGjaanan22/Products_CRUDS.git
cd Products_CRUDS/backend

Install dependencies:

npm install

Set up environment variables (e.g., .env file):

DB_HOST=your_host
DB_USER=your_user
DB_PASSWORD=your_password
DB_NAME=your_database

Run the backend server:

npm start

Frontend Setup (Angular)

Navigate to the frontend directory:

cd ../frontend

Install dependencies:

npm install

Start the Angular application:

ng serve

Open the application in your browser:

http://localhost:4200

API Endpoints

Category Master

Create Category: POST /api/categories

Get Categories: GET /api/categories

Update Category: PUT /api/categories/:id

Delete Category: DELETE /api/categories/:id

Product Master

Create Product: POST /api/products

Get Products: GET /api/products

Update Product: PUT /api/products/:id

Delete Product: DELETE /api/products/:id

Contributing

Feel free to raise issues or submit pull requests to enhance the project.

License

This project is licensed under the MIT License.

Developer: Gajanan Gangakhedkar

