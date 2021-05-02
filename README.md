# e-commerce_backend

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
![GitHub top language](https://img.shields.io/github/languages/top/nfinnegan/e-commerce_backend)

## Description 📁

This backend build out uses an Express.js API to connect to a mySQL database using sequelize, so we can perform CRUD operations on all of our tables (Category, Product, and Tags). This project is the culmination of last week's sprint where we learned sequelize and the significance of Object Relational Mapping (ORM).

## Getting Started

Once you've cloned down the repo, make sure to follow the installation instructions below. Once the dependencies have been installed, create a .env file to store your personal credentials and establish a connection with your database. Then use the schema.sql file to create your database, type `cat db/schema.sql | mysql -u root -p` into your terminal, enter your password if one exists. Feel free to use the seeds.sql file as well to get yourself started with dummy data ( to do so run `npm run seed`), or import your own. Once done, type `nodemon server.js` or `npm watch` to start listening on your dedicated localhost port. You will have the ability to create, update, delete, and find all existing database entries for all tables. Any changes you make will be saved to your database for future reference.

## User Story 👩

```md
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

## Technologies Used 💻

- Node.js
- JavaScript
- mysql, express, & sequelize npm packages

## Installation 💾

To install the necessary dependencies, please run the following (individually) in your terminal once you've navigated to the directory you've cloned the repo into:

        npm init -y
        npm i

## Preview 🔍

Check out the applications functionality below (watch full screen for optimal viewing):

-https://www.youtube.com/watch?v=Wx0H_bwkFCo

## License

This project is covered under the MIT license.
