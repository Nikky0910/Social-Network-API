# Social-Network-API

## Description

This is a backend API for a social network web application where users can share their thoughts, react to friends' thoughts, and maintain a friend list. The API is built using Express.js for routing and MongoDB as the database, with Mongoose as the ODM (Object Data Modeling) library.

## Technologies Used

- Node.js
- Express.js
- MongoDB
- Mongoose
- JavaScript Date object (or an optional JavaScript date library)

## Installation

Follow these steps to set up and run the e-commerce back-end project locally:

1. **Clone the Repository**  
   First, clone the repository to your local machine using the following command:

   ```bash
   git clone https://github.com/Nikky0910/Social-Network-API.git
    ```
2. **Navigate to the Project Directory**  
   After cloning, navigate to the project directory:

   ```bash
   cd social-network-api
    ```
3. **Install Dependencies**  
    Install the required Node.js packages by running:

   ```bash
   npm install
    ```
4. **Start the server**  
   Launch the application by running:

   ```bash
   npm start
    ```
    The server should start on  http://localhost:3001 or the port specified in your environment variables.

5. **Test the API**
   Use a tool like Insomnia or Postman to test the API routes.

## API Routes

**Users**

- GET /api/users - Get all users
- GET /api/users/:userId - Get a single user by ID
- POST /api/users - Create a new user
- PUT /api/users/:userId - Update a user
- DELETE /api/users/:userId - Delete a user
- POST /api/users/:userId/friends/:friendId - Add a friend
- DELETE /api/users/:userId/friends/:friendId - Remove a friend

**Thoughts**

- GET /api/thoughts - Get all thoughts
- GET /api/thoughts/:thoughtId - Get a single thought by ID
- POST /api/thoughts - Create a new thought
- PUT /api/thoughts/:thoughtId - Update a thought
- DELETE /api/thoughts/:thoughtId - Delete a thought

**Reactions**

- POST /api/thoughts/:thoughtId/reactions - Add a reaction to a thought
- DELETE /api/thoughts/:thoughtId/reactions/:reactionId - Remove a reaction from a thought

## Usage

Please refer to the following video to run the application:

<a href = "https://drive.google.com/file/d/1gg98Gk7z6wYrr9PCC6o48PoUtPlOJL2D/view?usp=drive_link"> Click here to watch the video</a>

Please refer to the following video on how to test the api routes using Insomnia: 

<a href = "https://drive.google.com/file/d/1zY1RC2hRNI8l9cxjpruehJjwOwx08Rzc/view?usp=drive_link"> Click here to watch the video</a>

## License

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
