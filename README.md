# Blogging Platform

A simple blogging platform built using Node.js, Express, MongoDB, and HTML/CSS. The platform allows users to create, view, edit, and delete blog posts via a RESTful API and provides a frontend interface for interacting with the blog.

## Features

- Custom pink theme
- Full CRUD (Create, Read, Update, Delete) operations for blog posts
- MongoDB integration using Mongoose
- Timestamped blog posts

## Prerequisites

Before you begin, ensure you have met the following requirements:

- [Node.js](https://nodejs.org/en/) installed 
- A code editor like [VSCode](https://code.visualstudio.com/)
- Register at [MongoDB](https://cloud.mongodb.com/) for database

## Installation and Setup

### Step 1: Create a Folder

Create a folder where all your working files will be stored. For example, you can name it `blogging-platform`.

### Step 2: Open the Folder in a Code Editor

Open the folder in your code editor, such as Visual Studio Code.

### Step 3: Initialize the Project and Install Dependencies

1. Initialize a new Node.js project by running:
   ```sh
   npm init -y
   ```
   This will create a `package.json` file with the default settings.

2. Install the necessary libraries for your project by running:
   ```sh
   npm install express dotenv mongoose body-parser
   ```

### Node.js Libraries Used:

- **Express**: A web framework for Node.js that simplifies server creation and handles routing and HTTP requests/responses.
- **Dotenv**: A module for loading environment variables from a `.env` file into `process.env`, used to store sensitive information like MongoDB connection URI securely.
- **Mongoose**: An ODM (Object Data Modeling) library for MongoDB and Node.js, used to interact with your MongoDB Atlas database by defining schemas and models.
- **Body-parser**: A middleware to parse incoming request bodies in a middleware before handling the request. It's used to extract JSON data from incoming POST/PUT requests.

### Step 4: Set up MongoDB

1. Create a free account at [MongoDB Atlas](https://cloud.mongodb.com/).
2. Create a new cluster and database.
3. Copy the MongoDB connection URI and store it in a `.env` file.

Your project is now set up and ready for further development!

## Running the Application

Once the environment is set up, you can run the application by using:
```sh
node server.js
```
By default, the app will be running on [http://localhost:5000](http://localhost:5000).

## Custom Styling
The project uses a pink color palette-style theme for the user interface. All the styles are defined in `styles.css`, and you can update colors by modifying the CSS in the `public/styles.css`.

## 💌 Contact
For issues or contributions, please feel free to open a pull request or contact me at aneleka87@gmail.com.

