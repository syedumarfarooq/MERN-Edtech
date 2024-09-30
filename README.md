# studynotion-edtech-project-main
## Overview
This project is an EdTech platform built using the MERN (MongoDB, Express, React, Node.js) stack. It provides functionalities for user authentication, course management, payment processing, and more.

The project is set up to run both the client (React) and server (Node.js/Express) concurrently using npm run dev.
## Features
User Authentication: Users can sign up, log in, and reset their password.<br>
Course Management: Instructors can create, update, and delete courses, while students can enroll and track progress.<br>
Payment Integration: Integrated with Razorpay for handling payments.<br>
Responsive Design: The frontend is built to be fully responsive for various devices.<br>
API with MongoDB: The backend uses MongoDB as the database for storing user and course data.<br>

## Installation and Setup
Follow the steps below to set up and run the project locally.

## Prerequisites
Node.js: Make sure Node.js is installed on your system. You can download it from nodejs.org.
MongoDB: Either install MongoDB locally or use MongoDB Atlas for cloud-hosted databases.
npm: Node Package Manager comes with Node.js.
______
## Steps
1.Clone the Repository


`git clone https://github.com/yourusername/edtech-mern-project.git
cd edtech-mern-project`<br>
2.Install Dependencies

Install dependencies for both the server and client.


`# Install server dependencies
cd server
npm install`

`# Install client dependencies
cd ../client
npm install`<br>
3.Configure Environment Variables

Create a .env file in the server folder. Below is an example of what your .env file should include:

`PORT=4000`  
`MONGO_URI=<your_mongodb_uri>`  
`JWT_SECRET=<your_jwt_secret>`  
`RAZORPAY_KEY_ID=<your_razorpay_key_id>`  
`RAZORPAY_KEY_SECRET=<your_razorpay_key_secret>`  
<br>
4.Run the Application

The project is set up to run both the client and server concurrently using npm run dev.

In the root directory (project folder), run the following command:


`npm run dev`
This will concurrently start both the server (Node.js/Express) and client (React) applications.
<br>
5.Access the Application

The server runs at: http://localhost:4000
The client runs at: http://localhost:3000
_____
## Scripts
Here are some useful npm scripts available in the project:

Server:
<br>
npm start: Runs the Node.js server.<br>
npm run dev: Runs the server with Nodemon for live-reloading during development.
<br>
Client:
<br>
npm start: Runs the React client in development mode.<br>
npm run build: Builds the React app for production.<br>
Root:
<br>
npm run dev: Runs both the server and client concurrently using concurrently.
