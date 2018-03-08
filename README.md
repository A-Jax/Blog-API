# Blog-API
An API for managing blog CRUD functionality. Blog mongoose model and a blog API written in Node.Js

Include the following in your back end app.js

const db = require('./config/database'); // DB config

const blogs = require('./routes/blog'); // import custom routing
app.use('/blog', blogs); // use the API
