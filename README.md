** Daily Journal **

This is a blog app study using node.js, express, ejs, mongodb atlas cloud database, mongoose, and lodash.

It is heavily based on [The Complete 2019 Web Development Bootcamp](https://www.udemy.com/the-complete-web-development-bootcamp/ "Udemy.com")  by Angela Yu, AppBrewery.

To setup:

(clone repository)
from your project folder:

`$ npm init`

create file `.env` with: 
CONNECT= \<mongodb connection string\>.
PORT=\<port\> [3000]
`$ node app.js`

Open browser tab with: `localhost:\<port\>`

App is basic, with console logging intact for future experimentation/augmentation. Styling is minimal. Features:
* mongodb atlas cloud database 
* mongoose mongodb middleware
* secrets (db connection string) maintained outside of source control in environment variables (uses dotenv package, .env file). 
* Lodash originally used for case adjustment (currently not used)
* ejs for html template rendering
