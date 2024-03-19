> markdown

# Recipe API

This project implements a simple recipe management system using Flask for the API and MSSQL for the database. It allows users to add, retrieve, update, and delete recipes, rate recipes, and add comments. 

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

> Installation

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

> docker-compose up --build

#### Usage ####

> markdown

Once the containers are up and running, you can access the API using the following endpoints:

- `POST /recipes`: Add a new recipe.
- `GET /recipes`: Retrieve a list of all recipes.
- `GET /recipes/<recipe_id>`: Retrieve details of a specific recipe.
- `PUT /recipes/<recipe_id>`: Update a specific recipe.
- `DELETE /recipes/<recipe_id>`: Delete a specific recipe.
- `POST /recipes/<recipe_id>/ratings`: Rate a specific recipe.
- `POST /recipes/<recipe_id>/comments`: Comment on a specific recipe.
- `GET /recipes/<recipe_id>/comments`: Retrieve all comments for a specific recipe.

### Evaluation Criteria

- Code quality, readability, and organization.
- Proper implementation of the API and database interactions.
- Proper use of Docker for containerization.
- Handling edge cases and error scenarios.

### Bonus Tasks

- Implementation of user authentication, search functionality, recipe suggestions, and unit tests.

## Authors

- Juliana Jasmin Aliswag | 3.19.2024
