# todolist
Todo List Web App
This is a simple web application for creating and managing todo lists. It uses Node.js with the Express framework for the backend, MongoDB as the database, and EJS as the templating engine for the frontend.


# Installation and Setup
Make sure you have Node.js and MongoDB installed on your system.

Clone this repository or download the code as a ZIP file and extract it to your desired location.

Open a terminal or command prompt and navigate to the project folder.

Install the required Node.js packages using npm (Node Package Manager). Run the following command:


npm install
Start the MongoDB server. If you have MongoDB installed globally, you can simply run:


mongod
Note: If you encounter any issues starting MongoDB, please refer to the official MongoDB documentation for troubleshooting.

Once MongoDB is running, you can start the web application. In the terminal, run:


node app.js
You should see a message indicating that the server has started on port 3000.

Open your web browser and go to http://localhost:3000 to access the todo list application.

# Usage
Home Page
The home page displays the "Today" todo list. Initially, it will contain some default items:

"Welcome to your todolist!"
"Hit the + button to add a new item."
"<-- Hit this to delete an item."
# Adding New Items
To add a new item to the "Today" list, simply enter the item's description in the input field provided and click the "+" button. The new item will be saved to the database and will appear in the list.

# Creating Custom Lists
You can create custom lists by adding the name of the new list to the URL. For example, to create a list called "Work", go to http://localhost:3000/Work. If the list already exists, it will be loaded; otherwise, a new list with the specified name will be created, and you will be redirected to the new list.

# Adding Items to Custom Lists
To add items to a custom list, navigate to the list by entering its name in the URL. Then, you can add new items using the input field and "+" button, just like with the "Today" list.

# Deleting Items
To delete an item from a list, click the checkbox next to the item, and then click the "Delete" button.

# About Page
The "About" page provides some information about this todo list web application.

# Technologies Used
Node.js
Express.js
MongoDB
Mongoose
EJS (Embedded JavaScript) - Templating engine for dynamic HTML rendering.








