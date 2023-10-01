# Language Learning Game

Prerequisites
Make sure you have the following software installed on your system:

Node.js and npm: Download and install Node.js
MongoDB: Install MongoDB
Getting Started
Clone this repository to your local machine:

bash
Copy code
git clone https://github.com/prehans/Learning-App
cd your-mern-app
Install dependencies for both frontend and backend:

bash
Copy code
# Install frontend dependencies
cd frontend
npm install

# Install backend dependencies
cd ../backend
npm install
Set up your MongoDB database:

Create a MongoDB database and update the connection URL in the backend/config/db.js file.
You can use a local MongoDB instance or a cloud-based service like MongoDB Atlas.
Configure environment variables:

In the backend/.env file, configure any environment variables your application needs, such as database credentials or API keys.
Start the backend server:

bash
Copy code
# From the server directory
npm start
Your backend server should now be running at http://localhost:5000.

Start the frontend development server:

bash
Copy code
# From the client directory
npm start
Your frontend development server should now be running at http://localhost:3000.

Open your web browser and navigate to http://localhost:3000 to access the application.
