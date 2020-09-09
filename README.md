# Project n ° 7 OpenClassrooms

## Creation of a corporate social network for Groupomania

Download the repository and follow the instructions below to install this project locally

## prerequisite

* Install Node.js
* Install Vue.js
* Install MySQL

## MySQL database

* Open your terminal
* Connect to MySQL: `mysql -h localhost -u root -p`
* Enter your password
* Create the database: `CREATE DATABASE groupomania_database CHARACTER SET 'utf8';`
* Use the created database: `USE groupomania_database`
* Import the groupomania_database.sql file: `SOURCE groupomania_database.sql;`
* In the backend folder, go to the connectdb.js file and enter your password in password: 'xxxxxx'

## Installing and starting the Backend

* Open your terminal
* Go to the backend folder: `cd groupomania-master / backend`
* Install all project dependencies: `npm install`
* Start the Node.js server: `nodemon server`

## Installing and starting the Frontend

* Open your terminal
* Go to the frontend folder: `cd groupomania-master / frontend`
* Install all project dependencies: `npm install`
* Start the application: `npm run serve`

## Test the application
* Open your browser and go to: `http: // localhost: 8080 /`