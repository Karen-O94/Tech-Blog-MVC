# Tech-Blog-MVC
A CMS-style blog site similar to a Wordpress site, where developers can publish their blog posts and comment on other developers’ posts as well. 

## Link to deployed app
[Tech Blog]()

## Screenshots

*Homepage*
![image](https://user-images.githubusercontent.com/74797740/112738892-db11b280-8f5e-11eb-9b60-759d9052bffe.png)

*Login Page*
![image](https://user-images.githubusercontent.com/74797740/112738910-02687f80-8f5f-11eb-9d02-1a614b4e75eb.png)

*Dashboard page with user logged in*
![image](https://user-images.githubusercontent.com/74797740/112738924-317ef100-8f5f-11eb-8b81-1b568bb0006c.png)

## Technology
* XAMPP / MySQL
* MySQl workbench
* Javascript
* Handlebars
* Heroku

## Installation
In order to use the ecommerce server, you will need to run `npm init -y` to initialise the `package.json ` and then install the following list of dependencies:
`npm i mysql2`
`npm i express`
`npm i sequelize`
`npm i express-session`
`npm i connect-session-sequelize`
`npm i dotenv`: to make sure this sensitive information i.e. password is hidden. 

The sequelize package allows us to map our object syntax on our database schemas. 

The mysql2 package connects you directly to the database created in the MySQL Workbench and you will need to create the database using the schema.sql file and running the command listed.  

Once all the dependencies are installed, you can initialise the application itself by running `node server.js` in the command line

## Usage 
After running `node server.js` to start the server and then go to Insomnia app and type in the routes you require to send or make a request and select the methods GET(READ), POST(CREATE), PUT(UPDATE), DELETE from the drop down list before clicking 'SEND'. 

Please see the example below of routes you will encounter with this app:

* GET all Blog Posts route - localhost:`${PORTnumber}`/eg. localhost:3001/
* GET  Blog Post by ID route - localhost:`${PORTnumber}`/post/`idNum` 
* POST routes - localhost:`${PORTnumber}`/`route`/
* UPDATE/PUT Blog Posts by ID route - localhost:`${PORTnumber}`/dashboard/edit/`idNum`
* DELETE Blog Post by ID route- localhost:`${PORTnumber}`/post/`idNum`

If all requests are successfully made, you will see the data populated in the Preview box and a status '200 OK'. A '404' or '400' status will show up if there is an error or bad request made

## Test
We do not have any test packages for this app but always check the error messages within terminals and debug using console.log(s). 

## License
[![MIT license](https://img.shields.io/badge/License-MIT-blue.svg)](https://lbesson.mit-license.org/)

> This project was created under the standard MIT licence.

> [Learn more about this licence.](https://lbesson.mit-license.org/)


## Questions?

Please contact me on the links below if you have any queries on how the application works or to view my other projects:

My GitHub username is Karen-O94 

Link to GitHub Profile: https://github.com/Karen-O94