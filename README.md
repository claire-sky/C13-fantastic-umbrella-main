# E-commerce Back End Starter Code

## Description
A back end for an e-commerce site using a working Express.js API and configured to use Sequelize to interact with a MySQL database.

[GitHub Repository](https://github.com/claire-sky/C13-fantastic-umbrella-main/)

[Video Walkthrough](https://watch.screencastify.com/v/wzVqt9IY1iZ3OVgY59Dn)

## Database Models and Associations
The database should contain the following four models:
* Category
* Product
* Tag
* ProductTag

The four models have the following relationships between them:

* Product belongs to Category, as a category can have multiple products but a product can only belong to one category.
* Category has many Product models.
* Product belongs to many Tag models. Using the ProductTag through model, allow products to have multiple tags and tags to have many products.
* Tag belongs to many Product models.

## Usage 

* Clone repository to local repository
* In the command line enter "npm install" to install node packages
* Use the environment variable to store you MySQL username and password.
* In the command line enter "mysql -u root -p" followed by your password
* Run "npm run seed" to seed data to the database for testing.
* In the command line enter "npm start" to start