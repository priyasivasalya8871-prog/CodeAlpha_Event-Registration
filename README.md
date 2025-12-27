# Event Registration System
This is a simple **Event Registration System** built using **Node.js, Express.js, MongoDB, and HTML**.  
Users can register for an event using a form, and the data is stored in MongoDB.

## Features
- Event registration using HTML form
- Backend API using Express.js
- Data stored in MongoDB using Mongoose
- REST API tested with Postman
- CORS enabled for frontend-backend communication

## Tech Stack
- Frontend: HTML, JavaScript
- Backend: Node.js, Express.js
- Database: MongoDB (MongoDB Compass)
- Tools: VS Code, Postman

## Installation & Setup
##Install dependencies
npm install
##Start MongoDB
mongodb://127.0.0.1:27017
##Run the server
node index.js
##Output
MongoDB connected
Server running on port 5000
##Register User
##POST
http://localhost:5000/register
##Request Body (JSON)
json
{
  "name": "Krishna",
  "email": "krishna@gmail.com",
  "event": "Tech Fest"
}
##Response
json
{
  "message": "Registered successfully"
}
##Get
http://localhost:5000/registrations




