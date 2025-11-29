# Full-Stack Book Store MERN App

A full-stack web application for managing a bookstore with features like **user authentication**, **admin dashboard**, **cart & checkout**, and **category-based filtering**.

## Tech Stack

- **Frontend:** React, Vite, Firebase Auth
- **Backend:** Node.js, Express.js
- **Database:** MongoDB (Mongoose)
- **Authentication:** JWT + Firebase

## How to Run This Project

### Frontend

1. Clone or unzip the project folder
2. Navigate to the frontend directory:
   ```bash
   cd frontend
3. Create a .env.local file in the frontend root directory and add Firebase environment variables:
    VITE_API_KEY="..."
VITE_AUTH_DOMAIN="..."
VITE_PROJECT_ID="..."
VITE_STORAGE_BUCKET="..."
VITE_MESSAGING_SENDER_ID="..."
VITE_APP_ID="..."
4. Install dependencies:
   npm install
5. Run the frontend:
   npm run dev

### Backend

1. Navigate to the backend directory:
cd backend
2. Install dependencies:
npm install
3. Create a .env file and add environment variables:
DB_URL="mongodb+srv://<username>:<password>@cluster0.mongodb.net/book-store?retryWrites=true&w=majority"
JWT_SECRET_KEY="your-secret-key"
4. Run the backend in development mode:
npm run start:dev


