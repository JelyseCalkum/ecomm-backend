# E-commerce Back End

SUMMARY

This project takes a working Express.js API and was configured to use Sequalize to interact with a MySQL database in order to build the back end for an e-commerce site. Using insomnia, a user can interact with the backend to view the products, categories, and tags aswell as use CRUD methods to alter the databse.

You can view the walkthrough video here:https://drive.google.com/file/d/1PahhFOFCIg2EqXMi9XFge8pWmFC0dfe1/view

Or you can check out the project files in my GitHub repository here: https://github.com/JelyseCalkum/ecomm-backend
 

INSTALLATION/USAGE

Clone the GitHub repo: https://github.com/JelyseCalkum/ecomm-backend
Once in the properly cloned folder, add a .env file to the root of the app with the following:


DB_NAME='ecommerce_db'

DB_USER='root'

DB_PW='YourPasswordHere'

Then run npm install to install dependencies (MySQL2 and Sequelize)
Create Schema and Seed data
Once the database has been populated, start the server on local host, then use Insomnia, or a similar application to make requests!


USER STORY

AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies


ACCEPTANCE CRITERIA

GIVEN a functional Express.js API.
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file, THEN I am able to connect to a database using Sequelize.
WHEN I enter schema and seed commands, THEN a development database is created and is seeded with test data.
WHEN I enter the command to invoke the application, THEN my server is started and the Sequelize models are synced to the MySQL database.
WHEN I open API GET routes in Insomnia Core for categories, products, or tags, THEN the data for each of these routes is displayed in a formatted JSON.
WHEN I test API POST, PUT, and DELETE routes in Insomnia Core, THEN I am able to successfully create, update, and delete data in my database.


ACKNOWLEDGEMENTS

Thank you to the UofO Coding Bootcamp for providing me the starter code as well as the tools and knowledge I needed to complete this project.

LICENSE

ISC
