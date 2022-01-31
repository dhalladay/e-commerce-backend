# E-commerce Backend Databse/API

  Example of an e-commerce backend API that was updated to use Sequelize from functioning starter code.
  
  ## Description

  Organized databases, and the API's that allow clients to interact with them, are an essential part of internet retail. This project uses the Sequelize ORM to create and organize a backend database/API that might be seen in an e-commerce site. It creates a set of tables that house product information and allows the client to add to, update and delete those records.

  ## Table of Contents

  * [Installation](#installation)
  * [Usage](#usage)
  * [Languages](#languages)
  * [Questions](#questions)
  * [Credits](#credits)

  ## Installation
  
  You will need node.js for this project. [Download it here](https://nodejs.org/en/download/) if you don't have it already.
  
  You will also likely need an API client such as [Insomnia](https://insomnia.rest/) to interact with the application.

  ### Prepare the project
  
  1. Clone code from [github](https://github.com/dhalladay/e-commerce-backend)
  2. Open a terminal and initialize npm by typing "npm init" into terminal
  3. Install npm dependecies by typing "npm install"
  4. Create a .env file with the variables listed in the /config/connection.js file.

  ### Create and seed the database 

  1. Log into mysql by typing "mysql -u <your username> -p" into the terminal
  2. Enter your password
  3. Once the mysql command line promp appears type "CREATE DATABASE ecommerce_db;"
  4. Type "quit"
  5. Once you have exited the mysql prompt, type "npm run seed" into the terminal to seed the database 

  ## Usage

  Once you have created and seeded your database, you'll need to start the server:

  1. Type "npm start" into the terminal
  2. Navigate to the local host using your API client or through a browser

  The following [video](https://youtu.be/pcEWMltg7jQ) demonstrates the functionality of the application using Insomnia

  ## Languages

  * Javascript
  * Node
  
  ## Questions

  Reach out on [github](https://github.com/dhalladay) with any questions:

  ## Credits

  Models and Routes: Dave Halladay

  Starter Code: Xandromus
  
