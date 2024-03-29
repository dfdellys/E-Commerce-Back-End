# E-Commerce-Back-End

In this project, I built the back end for an e-commerce site. I configured a working Express.js API to use Sequelize to interact with a MySQL database.

## User Story

```md
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

## Acceptance Criteria

```md
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia Core for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia Core
THEN I am able to successfully create, update, and delete data in my database
```

## Installation

```md
Clone repository and open in VS Code
Open Terminal on VS Code
Type npm install
Update the .env file with your MySQL password and user info
```

## Usage

```md
Open terminal on VS Code
Navigate to 'db'
Log in to MySQL
Type source schema.sql
Then quit
Navigate to main folder and type npm run seed
Run the app by typing node server.js
```

## Demo

* Part 1: https://watch.screencastify.com/v/RlpAy7HfS5AKtrrcSKx9
* Part 2: https://watch.screencastify.com/v/0dJFDhptEItgAQIWdOjZ

