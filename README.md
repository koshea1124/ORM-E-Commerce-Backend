# ORM-E-Commerce-Backend
##  Table of Contents
- [Description](#description)
- [Overview](#overview)
- [Technologies](#technologies)
- [Installation](#installation)
- [Link](#link)
- [Questions](#questions)
- [License](#license)
- [Credits](#credits)

##  Description
The e-commerce industry, a dominant force in the electronics sector, has reached staggering heights with an estimated $29 trillion in revenue generated in 2017. To remain competitive in this ever-growing landscape, internet retail companies must leverage the latest technologies. In this project, the challenge is to build the back end for an e-commerce site using Express.js API and Sequelize to interact with a MySQL database. By configuring the API and connecting it to the database, managers can ensure seamless data management and unleash the potential of their e-commerce website. The project includes creating a walkthrough video that showcases the application's functionality, meeting the specified acceptance criteria, and providing a comprehensive tool for competing in the dynamic e-commerce market.

##  Overview
###  The Challenge
The challenge is to build the back end for an e-commerce site. You’ll take a working Express.js API and configure it to use Sequelize to interact with a MySQL database.

###  User Story
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies

###  Acceptance Criteria
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia Core for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia Core
THEN I am able to successfully create, update, and delete data in my database

##   Technologies
* Express.js: A popular web application framework for Node.js that simplifies the development of server-side applications and APIs.
* Sequelize: An ORM (Object-Relational Mapping) library for Node.js that provides an easy way to interact with relational databases like MySQL. It handles database operations, relationships, and migrations.
* MySQL: A widely used open-source relational database management system. It stores the data for the e-commerce site and interacts with the back end through Sequelize.
* Environment Variables: A method for storing sensitive information, such as the database name, MySQL username, and MySQL password, securely outside of the code. These variables will be accessed using a dotenv package.
* Insomnia: Used to test and validate the functionality of the API routes for categories, products, and tags. It allows you to make HTTP requests and view the responses in a formatted JSON.
  
##  Installation
1. Node Package Manager (NPM): Open your terminal or command prompt and run the command "npm install" or "npm i" to install Node Package Manager and its dependencies.
2. Dotenv: In the root folder of your project, create a file named ".env".  Save your SQL login credentials in the .env file which allows for secure access to your MySQL database.
3. MySQL: Open the MySQL shell command line and xecute the command "source db/schema.sql" to import the database into your workspace. Once the import is complete, type "quit" to exit the MySQL shell.
4. Seeds: In the integrated terminal of your project's repository, run the command "npm run seed" or "node seeds/index.js". This command will seed the existing data to your database.
5. Connect to the Server: After completing the previous steps, start the server by running the command "npm start" or "node server.js" in your integrated terminal.
6. Insomnia: Download and install Insomnia, a free application for testing APIs. Insomnia will be a valuable tool for interacting with your application and testing its functionality.
   

By following these steps, you can effectively use the Express Note Taker application to create, view, and delete notes.

##  Link
Link to YouTube Video:

## Questions
Please feel free to reach out if you have any questions:
* GitHub UserName: https://github.com/koshea1124
* Email: koshea1980@gmail.com
  
## License
N/A

## Credits
* [NPM Inquirer](https://www.npmjs.com/package/inquirer)
* [Code Academy](https://www.codecademy.com/catalog)
* [Sequelize](https://sequelize.org/docs/v6/getting-started/)
* [MDN Docs](https://developer.mozilla.org/en-US/)
  
