# 🛍️ E-commerce RESTful API

A powerful and scalable E-commerce backend API built with **Node.js**, **Express**, and **MongoDB**, following best practices and clean architecture.

---

## 🚀 Features

- 🔐 User Authentication with JWT
- 👤 Roles: Admin & User
- 📦 CRUD Operations on Products
- 📂 Categories and Subcategories
- 🛒 Cart System (Add/Update/Delete)
- 🧾 Create & Manage Orders
- 💵 Cash Order Support
- 💳 Stripe Payment Integration
- ⭐ Product Reviews & Ratings
- 📊 Filtering, Sorting, and Pagination
- 📷 Image Uploads with Cloudinary
- ✅ Input Validation (express-validator)
- 🔒 Route Protection & Role-based Access
- 📁 MVC Project Structure

---

## ⚙️ Tech Stack

- Node.js + Express.js
- MongoDB + Mongoose
- JWT + bcrypt
- Cloudinary (image uploads)
- Stripe (payment)
- express-validator
- dotenv

---

## 🛠️ Installation
git clone https://github.com/khaled399/ecommerce-backend.git
cd ecommerce-backend
npm install
--

##  🚴‍♂️ Running the App
npm run dev

Or in production:
npm start
--

##🌐 API Structure (Sample)
| Route              | Method | Access | Description                |
| ------------------ | ------ | ------ | -------------------------- |
| /api/auth/register | POST   | Public | Register a new user        |
| /api/auth/login    | POST   | Public | Login and receive JWT      |
| /api/products      | GET    | Public | Get all products           |
| /api/products      | POST   | Admin  | Create a new product       |
| /api/cart          | GET    | User   | View user cart             |
| /api/orders        | POST   | User   | Create cash order          |
| /api/reviews       | POST   | User   | Add review on product      |
| /api/users         | GET    | Admin  | Get all users (admin only) |
--

##📁 .env Example
PORT=5000
DB_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
JWT_EXPIRES_IN=7d

STRIPE_SECRET_KEY=your_stripe_key
STRIPE_WEBHOOK_SECRET=your_webhook_key

CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret

EMAIL_HOST=smtp.example.com
EMAIL_PORT=587
EMAIL_USERNAME=your_email@example.com
EMAIL_PASSWORD=your_email_password
--
## ✍️ Author

**Khaled Ashraf**  
📧 khaled399@gmail.com  
🔗 [GitHub Profile](https://github.com/khaled399)

