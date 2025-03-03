# 17 NoSQL: Social Network API

![License](https://img.shields.io/badge/License-MIT-blue.svg)
<img alt="License" src="https://img.shields.io/badge/License-MIT-blue.svg">
<img alt="MongoDB" src="https://img.shields.io/badge/MongoDB-4.4+-green.svg">
<img alt="Express" src="https://img.shields.io/badge/Express-4.17+-green.svg">
<img alt="Mongoose" src="https://img.shields.io/badge/Mongoose-6.0+-green.svg">

## Description

A comprehensive backend API for a social network application built with MongoDB, Express.js, and Mongoose ODM. This API enables users to share thoughts, react to friends' posts, and manage friend connections - demonstrating the power of NoSQL databases for handling flexible, unstructured data in social networking platforms.

## Table of Contents

* [Installation](#installation)
* [Usage](#usage)
* [Contributing](#contributing)
* [API Routes](#APIRoutes)

* [License](#license)

* [Questions](#questions)

## Installation
-git clone https://github.com/your-username/nosql-social-network-api.git
-Navigate to the project directory
-npm install
-npm run build
-npm start

## Usage
Once the server is running, you can use API testing tools like Insomnia or Postman to interact with the API endpoints.

The API will be available at: http://localhost:3001

## APIRoutes
User Routes
GET /api/users - Get all users
GET /api/users/:userId - Get single user by ID with populated thought and friend data
POST /api/users - Create a new user
PUT /api/users/:userId - Update a user by ID
DELETE /api/users/:userId - Delete a user by ID (bonus: removes user's associated thoughts)
Friend Routes
POST /api/users/:userId/friends/:friendId - Add a friend to user's friend list
DELETE /api/users/:userId/friends/:friendId - Remove a friend from user's friend list
Thought Routes
GET /api/thoughts - Get all thoughts
GET /api/thoughts/:thoughtId - Get a single thought by ID
POST /api/thoughts - Create a new thought (and add to user's thoughts)
PUT /api/thoughts/:thoughtId - Update a thought by ID
DELETE /api/thoughts/:thoughtId - Delete a thought by ID
Reaction Routes
POST /api/thoughts/:thoughtId/reactions - Create a reaction for a thought
DELETE /api/thoughts/:thoughtId/reactions/:reactionId - Remove a reaction from a thought

## Contributing

Bradley Santiago

## License

This project is licensed under the MIT license.

## Questions

If you have any questions, please feel free to contact me at [BradleySantiago4@gmail.com](mailto:BradleySantiago4@gmail.com). You can also find more of my work at [https://github.com/revengelmfao](https://github.com/revengelmfao).
