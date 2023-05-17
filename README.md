# Project Description:

  The CRUD (Create, Read, Update, Delete) application is a powerful and flexible web application built using Node.js, Express.js, and MongoDB. This application is designed to simplify the management of data by providing seamless operations to create, read, update, and delete records in a MongoDB database. The purpose of this project is to provide a user-friendly interface and a robust backend system for performing CRUD operations on various data entities.


 # Technologies Used
    Node.js
    Express.js
    MongoDB                      
                      
# Prerequisites

Before running this CRUD application, ensure that you have the following prerequisites installed:

    Node.js: Make sure you have Node.js installed on your machine. You can download it from the official website: Node.js

    MongoDB: Install MongoDB on your machine or use a cloud-based MongoDB service. Make sure you have the MongoDB connection URL ready to configure the application.

    Git: Install Git on your machine to clone the project repository and manage version control.

    Text Editor: Choose a text editor of your preference, such as Visual Studio Code, Sublime Text, or Atom, to work with the project files.
    
# Frontend Specifications:

  The frontend of this CRUD application is developed using EJS (Embedded JavaScript) as the templating engine. EJS allows the dynamic rendering of HTML templates with embedded JavaScript code, providing a seamless integration between frontend and backend components.
  
# Backend Specifications:

  The backend of this CRUD application is built using Node.js and Express.js, providing a robust and scalable server-side architecture.  It utilizes MongoDB Atlas, a cloud-based database service, accessed through Compass, a GUI tool for managing MongoDB databases. This application simplifies data management by providing seamless CRUD operations on the MongoDB Atlas database.It interacts with the MongoDB Atlas database through the MongoDB Node.js driver, ensuring seamless connectivity and efficient data operations.

# API Routes
    GET /api/users: Retrieve all users from the database.
    POST /api/users: Create a new user in the database.
    GET /api/users/:id: Retrieve a specific user by ID.
    PUT /api/users/:id: Update a specific user by ID.
    DELETE /api/users/:id: Delete a specific user by ID.
   
# Key Features and Functionalities:
      Create: Users can easily create new records by filling out forms or providing necessary details through API requests. The application ensures data integrity and validation before saving it to the database.
      
      Read: The application provides efficient and optimized retrieval of data from the MongoDB database. Users can fetch specific records based on criteria, such as filtering by specific fields or querying with specific parameters.
      
      Update: Users have the ability to update existing records, modifying specific fields or updating the entire record altogether. The application handles data validation and ensures consistency in the updated information.
      
      Delete: This application allows users to remove records from the database, providing a seamless way to delete unwanted or outdated data. It ensures proper handling of related data dependencies and maintains referential integrity.
      
                      
Installation
To run this CRUD application, follow these steps:

Clone the repository to your local machine using the following command:

    git clone https://github.com/sindhueswar/assignment4.git
Navigate to the project directory:

    cd assignment4
Install the dependencies by running the following command:

    npm install
Create a MongoDB cluster and obtain the connection URL. You can set up a cluster on the MongoDB Atlas cloud service or use a local MongoDB server. Make sure you have the connection URL available.

Open the project in a text editor and locate the config.js file in the config folder.

Update the MONGO_URI field in the config.js file with your MongoDB connection URL:


    module.exports = {
      MONGO_URI: 'YOUR_MONGODB_CONNECTION_URL',
    };
Replace YOUR_MONGODB_CONNECTION_URL with the actual MongoDB connection URL.

Save the config.js file.

Start the application by running the following command:

    npm start
The application will be running at http://localhost:3000.

Open your web browser and navigate to http://localhost:3000 to access the CRUD application.          
                      
