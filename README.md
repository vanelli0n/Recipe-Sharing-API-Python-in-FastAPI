> markdown

# Recipe API

This project implements a simple recipe management system using Flask for the API and MSSQL for the database. It allows users to add, retrieve, update, and delete recipes, rate recipes, and add comments. 

## Getting Started

To run the application, make sure you have Docker installed on your machine.

1. Clone this repository:

> css

# git clone https://github.com/vanelli0n/recipe-api.git

2. Navigate to the project directory:

> arduino

#cd recipe-api

3. Build and run the application using Docker:

> sql

# docker-compose up --build

4. Access the API at http://localhost:5000

## API Endpoints

- POST /recipes/: Add a new recipe.
- GET /recipes/: Retrieve a list of all recipes, sorted by most recent.
- GET /recipes/<recipe_id>: Retrieve details of a specific recipe by its ID.
- PUT /recipes/<recipe_id>: Update a specific recipe by its ID.
- DELETE /recipes/<recipe_id>: Delete a specific recipe by its ID.
- POST /recipes/<recipe_id>/ratings/: Rate a specific recipe.
- POST /recipes/<recipe_id>/comments/: Comment on a specific recipe.
- GET /

### recipes/<recipe_id>/comments/: Retrieve all comments for a specific recipe.
