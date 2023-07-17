# Assignment10


## Table of contents  
* [Objective](#Objective)
* [Task Description](#Task-description)
* [Installation](#Installation)
* [Usage](#Usage)
* [Postman](#Postman)
* [Screenshots](#Screenshots)
* [Server-side Data Validation](#Server-side-data-validation)
  
## Objective

Create a CRUD web application for a blogging platform, incorporating database relationships using Sequelize, and implementing user authentication and authorization.

## Task Description

*

## Installation

Clone the repository to your local machine

Open a terminal and navigate to the project directory

Install the dependencies by running the following command:

```
npm install
```
Make sure the .env file is set up with the correct variables (DB_USER, DB_PASSWORD, DB_NAME, and DB_HOST) and is located in the root of our project directory. The .env file is not committed to version control, so you'll need to create a new one.
```
DB_USER=
DB_HOST=
DB_NAME=
DB_PASSWORD=
DB_PORT=
```
Now, when we run our application in development mode, Sequelize will use the credentials provided in our environment variables to connect to our database.

## Usage

To start the application, run the following command in your terminal:

```
npm start
```

This will start the server on port 4000 by default. You can access the API using any REST client, such as a ReactJS app, Postman or cURL.

The following endpoints are available:

- GET /posts - Retrieve a list of all posts.
- GET /posts/:id - Retrieve a specific post by ID.
- POST /posts - Create a new post.
- PATCH /posts/:id - Update a specific post by ID. 
- DELETE /posts/:id - Delete a specific post by ID.
  
- GET /comments/:id - Retrieve a specific comment by ID.
- GET /posts/:id/comments - Retrieve all comments for a specific post.
- POST /comments - Create a new comment.
- PATCH /comments/:id - Update a comment. 
- DELETE /comments/:id - Delete a comment.

- POST /signup
- POST /login
- DELETE /logout

## Postman
Link to Postman Collection: https://www.postman.com/mdegrezia/workspace/blogging-platform-api/collection/28381226-12442454-c3bd-41db-93b0-cc5b5570ce7e?action=share&creator=28381226

## Screenshots

