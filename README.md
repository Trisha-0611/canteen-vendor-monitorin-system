The Canteen Vendor Monitoring System is designed to simplify the management of canteen operations by providing administrators with a secure and user-friendly platform. It enables efficient management of vendors, food items, customer orders, inventory, and business insights through interactive dashboards.

---

## ✨ Features

### 🔐 Authentication
- User Registration
- Secure Login
- JWT Authentication
- Password Encryption using bcrypt

### 🍔 Food Management
- Add Food Items
- View Food Menu
- Update Food Details
- Delete Food Items
- Manage Stock

### 🏪 Vendor Management
- Add Vendors
- Update Vendor Information
- Delete Vendors
- View Vendor Details

### 📦 Order Management
- Place Orders
- View Orders
- Update Order Status
- Track Order Workflow

### 📊 Dashboard & Analytics
- Total Vendors
- Total Food Items
- Total Orders
- Revenue Overview
- Sales Analytics
- Vendor Performance
- Interactive Charts

---

## 🛠️ Tech Stack

### Frontend
- React.js
- Vite
- Tailwind CSS
- Axios
- React Router DOM
- Recharts
- Framer Motion
- React Icons

### Backend
- Node.js
- Express.js
- MongoDB Atlas
- Mongoose
- JWT Authentication
- bcrypt

---

## 🏗️ Project Architecture

```
User
   │
   ▼
React Frontend
   │
Axios API Calls
   │
Express Backend
   │
Mongoose
   │
MongoDB Atlas
```

---

## 📂 Folder Structure

```
canteen-vendor-monitoring-system
│
├── client
│   ├── src
│   ├── public
│   └── package.json
│
├── server
│   ├── controllers
│   ├── middleware
│   ├── models
│   ├── routes
│   ├── .env
│   ├── server.js
│   └── package.json
│
└── README.md
```

---

## 🚀 Installation

### Clone Repository

```bash
git clone https://github.com/yourusername/canteen-vendor-monitoring-system.git
```

---

### Backend Setup

```bash
cd server
npm install
npm start
```

Backend runs on:

```
http://localhost:5000
```

---

### Frontend Setup

```bash
cd client
npm install
npm run dev
```

Frontend runs on:

```
http://localhost:5173
```

---

## 📡 API Endpoints

### Authentication

```
POST /api/auth/register
POST /api/auth/login
```

### Food

```
GET    /api/food
POST   /api/food/add
PUT    /api/food/:id
DELETE /api/food/:id
```

### Vendors

```
GET    /api/vendors
POST   /api/vendors/add
PUT    /api/vendors/:id
DELETE /api/vendors/:id
```

### Orders

```
GET    /api/orders
POST   /api/orders/place
PUT    /api/orders/:id/status
```

---

## 📈 Future Enhancements

- Email Notifications
- QR Code Based Ordering
- Online Payment Integration
- Vendor Performance Reports
- Inventory Prediction
- AI-based Demand Forecasting
- Mobile Responsive PWA

---

## 📸 Screenshots

Add screenshots of:

- Login Page
- Dashboard
- Food Management
- Vendor Management
- Order Management
- Analytics Dashboard

---

## 👩‍💻 Developed By

**Trisha Bej**

Summer Internship Project

**Tata Steel Limited**

---
