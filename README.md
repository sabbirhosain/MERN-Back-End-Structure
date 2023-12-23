﻿### MERN-Back-End-Structure

 <pre>

(1)   =>  package.json create         =>    npm init -y
(2)   =>  package.json(file) input    =>    "type":"module"  =>  for ES6 (file import syntex)
(3)   =>  gitignore generator         =>    https://mrkandreev.name/snippets/gitignore-generator/




  
(4)   =>  create project root/src folder

|-- src/config/                  # "src" folder inside the "config" folder
|   |-- database.js              # Database configuration file
|
|-- src/controllers/             # "src" folder inside the "controllers" folder
|   |-- user.controller.js       # Controller for user-related operations
|
|-- src/middlewares/             # "src" folder inside the "middlewares" folder
|   |-- user.middleware.js       # Middleware for authentication
|
|-- src/models/                  # "src" folder inside the "models" folder
|   |-- user.model.js            # MongoDB model for User
|
|-- src/routes/                  # "src" folder inside the "routes" folder
|       |-- user.route.js        # API routes for user-related operations
|
|-- app.js                 # Main Express application file
|-- index.js               # Entry point for the Node.js server
|-- .env                   # Environment variables configuration
|-- .gitignore             # Node.js project configuration file


*** Backend package list

1.  npm init -y               =>  npm initialize package.json
2.  npm i nodemon             =>  auto reload server
3.  npm i dotenv              =>  environment variables configuration
4.  npm i cors                =>  database middleware for a Node.js
5.  npm i mongoose            =>  Mongoose is a MongoDB library
5.  npm i express             =>  express is a node.js framework
6.  npm i colors              =>  terminal colors



folder create command   =>  mkdir folderName
file create command     =>  
chack directory         => dir
change directory next   => cd folderName
change directory prev   => cd ..





   
 </pre>
