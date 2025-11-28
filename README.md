# 🛒 E-Commerce Application (MERN Stack)

This is a **full-stack E-commerce application** built using the **MERN stack (MongoDB, Express.js, React.js, Node.js)**. It allows users to browse products, manage their cart, place orders, and make payments. Admins can manage products, users, and orders efficiently.

---

## 🚀 Features

### ✅ User Features
- Browse and search products
- Product details page
- Cart management
- User authentication (JWT-based login & registration)
- Profile management
- Order tracking and payment processing
- Review and rate products

### 🔑 Admin Features
- Admin dashboard
- Manage products (CRUD operations)
- Manage users
- Manage orders & update order status

---

## 🛠️ Tech Stack
- **Frontend**: React.js, React Router, Tailwind CSS, Toastify
- **Backend**: Node.js, Express.js, MongoDB, Mongoose
- **Authentication**: JWT, bcrypt.js
- **Middleware**: Express, CORS, dotenv

---

## 📂 Project Structure
```
E-Commerce-App/
├── backend/    # Node.js + Express.js + MongoDB (API)
├── frontend/   # React.js + Tailwind CSS (UI)
└── README.md   # Main project documentation
```

---

## ⚙️ Installation & Setup

1. **Clone the repository:**
   ```sh
   git clone https://github.com/Praneeth76/E-commerce.git
   cd ecommerce-app
   ```

2. **Setup Backend:**
   ```sh
   cd backend
   npm install
   ```
   - Configure `.env` file with MongoDB connection & JWT secret.
   - Start the backend server:
     ```sh
     npm start
     ```

3. **Setup Frontend:**
   ```sh
   cd ../frontend
   npm install
   npm start
   ```

4. **Access the Application:**
   - Frontend: `http://localhost:5173`
   - Backend API: `http://localhost:5000`
   - Hosted Website: [Live Demo](https://your-vercel-app.vercel.app)

---

## 📜 License
This project is licensed under the **MIT License**.

Happy Coding! 🚀

