# Blog-API
An API for managing blog CRUD functionality. Blog mongoose model and a blog API written in Node.Js. Can be used with frameworks like Angular, React, Knockout, or template engines like Handlebars, EJS.

Include the following in your back end app.js

const db = require('./config/database'); // DB config

const blogs = require('./routes/blog'); // import custom routing
app.use('/blog', blogs); // use the API

router exported as blog. So the url will be localhost:4200/blog/new etc.

Enjoy!
