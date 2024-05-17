REST API Server
Overview
This project implements a REST API server with CRUD functionalities using Node.js with Express. The API allows users to Create, Read, Update, and Delete data stored in a MongoDB database.

Requirements
Node.js and npm (for Node.js implementation)
Express js
MongoDB
Setup
Node.js with Express
Install dependencies:

npm install express mongoose body-parser
Run the server:

node server.js
Endpoints:

POST /items: Create a new item.
GET /items: Retrieve all items.
GET /items/:id: Retrieve a specific item by ID.
PUT /items/:id: Update an item by ID.
DELETE /items/:id: Delete an item by ID.

Run the server:

npm run dev
Endpoints:

POST /items: Create a new item.
GET /items: Retrieve all items.
GET /items/:id: Retrieve a specific item by ID.
PUT /items/:id: Update an item by ID.
DELETE /items/:id: Delete an item by ID.
Database Configuration
Ensure that MongoDB is installed and running. The default configuration connects to a MongoDB instance running locally at mongodb://localhost:27017/mydatabase.

screenshots
gat all movies.
![Screenshot 2024-05-17 143008](https://github.com/vamsiKrishna-511/credence_backend_assignment/assets/116443206/d4473bbc-f029-4bfd-acb3-085c1d5c42f4)
gat a movie based on id.
![Screenshot 2024-05-17 142739](https://github.com/vamsiKrishna-511/credence_backend_assignment/assets/116443206/88d0c6e4-577b-4275-84cf-54a4f61fb37c)
