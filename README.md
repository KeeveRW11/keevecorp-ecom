# keevecorp-ecom


  ## Table of Contents
  * [Description](#description)
  * [Installation](#installation)
  * [Usage](#usage)
  * [Contribution Guidelines](#contribution)
  * [Test](#test)
  * [License](#license)
  * [For More Details](#questions)
  ## Description
  This is a project contains important files needed for the back end of an e-commerce website. We use the concepts of Object-Relational Mapping (ORM) to create and populate the data needed for the site.
  ## Installation 
  This app requires node.js, express.js sequelize and dotenv. For loading this project properly the information needs to be uploaded using npm run seed.
  ## Usage 
  This app can be used to save data for easy task to keep you up to date on things you need to get done. You have the option to save delete and retrieve saved notes.
  ## Contribution Guidelines
  Please contact below for further instructions if required.
  ## Test
 In order to test the functionality of the app, please check to ensure that the databases were properly uploaded to MYSQL. Once that is done, open the insomnia app and test API POST, PUT, and DELETE for Category Product and Tag tables.
  ## License
  ![Unlicensed](https://img.shields.io/badge/license-Unlicense-blue.svg)
  ## For More Details
  Contact me:
  Github:[https://github.com/KeeveRW11/keevecorp-ecom](https://github.com/KeeveRW11)
  Email:[keevewhyte+github@gmail.com](keevewhyte+github@gmail.com)
  Video: [https://drive.google.com/file/d/1PWKObgTFxx4DZJFNxFgR0itCTS_x2gtz/view]

# User Story
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete data in my database
