# E-Commerce-Back-End
# Table of contents
* [User Story](#user-strory)
* [Acceptance Criteria](#acceptance-criteria)
* [Installation Instructions](#installationinstructions)
* [Usage](#usage)
* [Video Example](#video-example)

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
WHEN I open API GET routes in Insomnia for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete data in my database

## Installation Instructions 
Clone this repository to your machine and create your own .env file with mySQL credentials. Be sure to run "npm i" to install associated packages.

## Usage 
Once files are properly installed navigate to E-commerce-Back-End in your command line. Run "mysql -u root -p" and then enter your mySQL password. Now that you are logged in you are able to establish your database.Run source [path to your schema.sql]. Seed database in files or update using server connection. Run "npm run start" to get server listening then you can run testing on routes using insomnia.

## Video Example
https://www.youtube.com/watch?v=4ijQD39aKQY

## Questions 
If you have any questions about this project please contact me via email: <gnosisknows28@gmail.com>