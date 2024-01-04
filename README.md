# E-Commerce Backend

## Description

This application is an example of the backend of an e-commerce site.  This app was created using Express, MySQL, Sequelize, Express, and Javascript.  Testing was done using Insomnia.

## Installation

Run npm install to update the required packages. Create a .env file with your MySQL information included. Use MySQL shell to create the database by running SOURCE db/schema.sql;. QUIT out of MySQL shell. Seed the database by running npm run seed. Start your server by running npm start. Since there is no frontend, using Insomnia is crucial to ensuring functionality.

## Usage

Insomnia or another API testing application should be used to use this application.

Find All Categories: GET /api/categories/
Find All Products: GET /api/products/
Find All Tags: GET /api/tags/
Find One Category: GET /api/categories/:id/
Find One Product: GET /api/products/:id/
Find One Tag: GET /api/tags/:id/

Create A Category: POST /api/categories/ with JSON object in request
Create A Product: POST /api/products/ with JSON object in request
Create A Tag: POST /api/tags/ with JSON object in request

Update A Category: PUT /api/categories/:id/ with JSON object in request
Update A Product: PUT /api/products/:id/ with JSON object in request
Update A Tag: PUT /api/tags/:id/ with JSON object in request

Delete A Category: DELETE /api/categories/:id/
Delete A Product: DELETE /api/products/:id/
Delete A Tag: DELETE /api/tags/:id/

## Demo and Screenshot



## Credits

Resources used include previous classwork and Stack Overflow.

## Contact Me

Email: nickalmond14@gmail.com
Github: almondnick