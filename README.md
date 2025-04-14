
---
# 🛠️ E-Commerce 2025 Back-End API

A scalable, secure, and RESTful API for the E-Commerce 2025 platform — handling product, user, order, and payment operations with JWT authentication and Stripe integration.

## ✨ Features
- User Authentication & Authorization (JWT)
- Order, Product, and User CRUD
- Secure Payment Processing with Stripe
- Coupon and Discount Code Generator
- Analytics Data Endpoints for Dashboard Charts
- RESTful API Design
- Global Error Handling & Validation
- Admin APIs:
  - Orders and transaction management
  - Product inventory management
  - Coupon management
  - User management (CRUD)
  - Dashboard analytics (revenue, transactions, gender ratios)


## 📦 Tech Stack
- Node.js + Express.js
- MongoDB with Mongoose / PostgreSQL (as needed)
- JWT for Authentication
- Stripe for Payments
- Zod / Joi for Validation
- Cloudinary / S3 for Image Uploads
- Multer
- Node-Cache
- Morgan
- CORS

## 📈 Endpoints Example
| Method | Endpoint               | Description |
|:--------|:------------------------|:--------------|
| GET     | /api/products            | Fetch products |
| POST    | /api/products            | Create product |
| POST    | /api/auth/login          | User login |
| POST    | /api/orders/checkout     | Process checkout |



**Environment Variables:**

```
PORT=4000
MONGO_URI=your_mongo_uri
STRIPE_KEY=your_stripe_secret_key
```

## 📦 Installation

```bash
git clone <backend-repo-url>
cd backend
npm install
npm run dev
