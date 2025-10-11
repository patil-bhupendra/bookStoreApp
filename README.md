##Full-Stack Book Store MERN App

A full-stack web application for managing a bookstore with features like user authentication, admin dashboard, cart & checkout, and category-based filtering.

##Tech Stack

#Frontend: React, Vite, Firebase Auth

#Backend: Node.js, Express.js

#Database: MongoDB (Mongoose)

#Authentication: JWT + Firebase

##How to Run This Project
#Frontend

Clone or unzip the project folder.

Navigate to the frontend directory:

cd frontend


Create a .env.local file in the frontend root directory (same level as package.json) and add the following Firebase environment variables:

VITE_API_KEY="AIzaSyCXvDIC4MPrkaMdeg_O2iij88wLpfj3qBA"
VITE_AUTH_DOMAIN="book-store-mern-app.firebaseapp.com"
VITE_PROJECT_ID="book-store-mern-app"
VITE_STORAGE_BUCKET="book-store-mern-app.appspot.com"
VITE_MESSAGING_SENDER_ID="205632822247"
VITE_APP_ID="1:205632822247:web:b0db0ec66bf6de0bbb3b42"


##Install dependencies:

npm install


Run the frontend:

npm run dev

Backend

Navigate to the backend directory:

cd backend


##Install dependencies:

npm install


#Create a .env file in the backend root directory (same level as package.json) and add the following environment variables:

DB_URL="mongodb+srv://<username>:<password>@cluster0.mongodb.net/book-store?retryWrites=true&w=majority"
JWT_SECRET_KEY="your-secret-key"


Note: Make sure MongoDB is set up and replace <username>, <password>, and the JWT secret key accordingly.

##Run the backend in development mode:

npm run start:dev

Additional Notes

Ensure both frontend and backend are running concurrently for full functionality.

Firebase configuration is required for authentication features.

MongoDB Atlas is recommended for the database setup.
