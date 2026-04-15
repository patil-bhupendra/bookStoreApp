# 📚 Full-Stack Bookstore Web Application (MERN)

🚀 **Live Demo:** https://book-store-camp.vercel.app/

A production-ready full-stack Bookstore Web Application built using the MERN stack. It enables users to browse books, manage cart & orders, and provides an admin dashboard to manage inventory and track business insights.

---

## ✨ Features

### 👤 User Features
- Secure authentication using **JWT + Firebase**
- Browse books with **category-based filtering**
- Add to cart and manage items
- Smooth **checkout & order placement**
- View order history
- Fully responsive UI

### 🛠 Admin Features
- Admin dashboard for **book & order management**
- Add, update, delete books
- Monitor orders and platform activity
- View analytics via admin stats

---

## 🚀 Key Highlights

- 🔐 Implemented **role-based authentication (User/Admin)**
- 🧠 Structured backend using **MVC architecture**
- ⚡ Efficient API handling using **Redux Toolkit Query**
- 📊 Admin analytics module for tracking performance
- 🔄 RESTful APIs with clean separation of concerns
- 🎯 Optimized frontend with reusable components

---

## 🛠 Tech Stack

**Frontend:**  
React.js, Vite, Tailwind CSS, Redux Toolkit, RTK Query  

**Backend:**  
Node.js, Express.js  

**Database:**  
MongoDB (Mongoose)  

**Authentication:**  
JWT + Firebase Authentication  

---

## 🔗 API Endpoints

### 📘 Books
- `GET /api/books` → Get all books  
- `POST /api/books` → Add new book (Admin)  
- `PUT /api/books/:id` → Update book (Admin)  
- `DELETE /api/books/:id` → Delete book (Admin)  

### 📦 Orders
- `POST /api/orders` → Place order  
- `GET /api/orders` → Get user orders  

### 👤 Users
- `POST /api/auth` → Login/Register user  

---

## 📸 Screenshots

<!-- Replace with actual images -->
![Home](./frontend/src/assets/banner.png)
![Books](./frontend/src/assets/books/book-1.png)
![Dashboard](./frontend/src/assets/github-cover.png)

---

## 🔑 Demo Credentials

**User Login:**  
Email: testuser@gmail.com  
Password: 123456  

**Admin Login:**  
Email: admin@gmail.com  
Password: 123456  

---

## ⚙️ Setup Instructions

### 🔹 Clone the Repository
```bash
git clone https://github.com/patil-bhupendra/bookStoreApp.git
```
cd bookStoreApp

### 🔹 Frontend Setup
```
cd frontend
npm install
npm run dev
```

Create a .env.local file and add:

```
VITE_API_KEY=your_key
VITE_AUTH_DOMAIN=your_domain
VITE_PROJECT_ID=your_project_id
VITE_STORAGE_BUCKET=your_bucket
VITE_MESSAGING_SENDER_ID=your_sender_id
VITE_APP_ID=your_app_id
```

### 🔹 Backend Setup
```
cd backend
npm install
npm run start:dev
```

Create a .env file and add:
```
DB_URL=your_mongodb_url
JWT_SECRET_KEY=your_secret
```
### 📁 Project Structure
```
bookStoreApp/
│── frontend/        # React frontend
│── backend/         # Express backend (MVC)
│── README.md
```
### 🚀 Future Improvements
💳 Payment integration (Stripe / Razorpay)
❤️ Wishlist functionality
📦 Order tracking system
⚡ Performance optimization & caching

###🙌 Author

**Bhupendra Patil**
📧 bhupendrarajput1232@gmail.com

🔗 GitHub: https://github.com/patil-bhupendra

### ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub!
