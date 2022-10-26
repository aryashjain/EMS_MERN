# Employee_Management_System
This is a project created by nodejs , express , mongodb and ejs that helps us to manage the employee data
functions supported by this app are
Create a new employee
Read and display the existing employee data
Update the existing employee
Delete the data from the db

#### To Run this project Clone it and install modules using
```
npm install
or
1.npm init
2.npm i express morgan nodemon ejs body-parser dotenv mongoose axios
```

```
npm start
```

these dependencies have following functions
1. express -
2. nodemon -automatically refreshes and restarts the server with the required changes
3. morgan - HTTP request logger middleware for node.js
4. ejs - EJS is a simple templating language that lets you generate HTML markup with plain JavaScript. No religiousness about how to organize things. No reinvention of iteration and control-flow. It's just plain JavaScript.
5. body-parser- Parse incoming request bodies in a middleware before your handlers, available under the req.body property. 
6. dotenv -Dotenv is a zero-dependency module that loads environment variables from a .env file into process.env
 this is used for security purposes. 
7. mongoose -Mongoose provides a straight-forward, schema-based solution to model your application data. It includes built-in type casting, validation, query building, business logic hooks and more, out of the box.
8. axios-Promise based HTTP client for the browser and node.js