# Househunting
# 🏠 HouseHunt: Finding Your Perfect Rental Home

**HouseHunt** is a full-stack rental property web application designed to simplify the process of finding, listing, and managing rental homes and apartments. Built with the **MERN stack** (MongoDB, Express, React, Node.js), it offers distinct experiences for Renters, Property Owners, and Admins.

---

## 🌐 Live Demo

🔗 [View Live Site](https://househunt-app.vercel.app)

---

## ✨ Features

### 👥 User Roles
- **Renter**: Browse, filter, and book rental homes
- **Owner**: Add, manage, and update property listings
- **Admin**: Approve owners, monitor users, and manage governance

### 🏡 Property Features
- Image-rich property listings
- Smart filters (location, price, bedrooms, etc.)
- Direct inquiry and booking system

### 🔐 Authentication
- Role-based login and registration (JWT)
- Secure booking requests
- Admin approvals

---

## 🛠️ Tech Stack

| Layer           | Technology                      |
|----------------|----------------------------------|
| Frontend        | React.js, Tailwind CSS, Axios    |
| Backend         | Node.js, Express.js, JWT Auth    |
| Database        | MongoDB                          |
| Deployment      | Vercel (Frontend), Render/Local (Backend) |

---

## 🧪 Test Accounts

| Role    | Email                         | Password   |
|---------|-------------------------------|------------|
| Renter  | renter.user@example.com       | renter123  |
| Owner   | owner.user@example.com        | owner123   |
| Admin   | admin@househunt.com           | admin123   |

---

## 📂 Project Structure

```bash
HouseHunt/
├── client/              # React frontend
│   ├── components/
│   ├── pages/
│   └── App.js
├── server/              # Node.js backend
│   ├── controllers/
│   ├── routes/
│   ├── models/
│   └── server.js
└── README.md
