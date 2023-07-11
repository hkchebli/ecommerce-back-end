# employee-tracker
> This program is a back end for an e-commerce site. It uses Express.js API Sequelize to interact with a MySQL database.

## Table of contents
* [User Story](#user-story)
* [Instructions to Install](#instructions)
* [Technologies](#technologies)
* [Sources](#sources)
* [Video Demo](#video-demo)
* [Link](#Link)


## User Story
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies

## Instructions
To run this app locally:

1. Pull down and/or branch this repository
2. IN YOUR TERMINAL: Run ```npm install``` to install all dependencies 
3. log in to mysql using ```mysql -uroot -p```
4. in mysql, run ```source db/schema.sql``` and ```show databases``` to make sure db_ecommerce was created
5. Exit mysql and run ```npm run seed```, then run ```npm start```
6. open insomnia and open http://localhost:3001/api
7. uses /categories, /tags, /products to check the results

## Technologies
* Javascript
* Node.js
* Sequilize
* MySQL
* Express.js
* .env

## Sources

* [MySQL](https://www.npmjs.com/package/mysql)
* [Express.js](https://expressjs.com/en/api.html)

## Video Demo
* [DEMO](https://www.youtube.com/watch?v=O0g5WKl_Ksw)

## Link
* [Github] https://github.com/hkchebli/ecommerce-back-end