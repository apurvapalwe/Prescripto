# 💊 MediConnect – Full Stack Medical Appointment Platform

MediConnect is a full-stack MERN application built to streamline the process of booking doctor appointments. It features separate portals for users and administrators, real-time slot management, authentication, and a clean responsive UI.


---

## 🔧 Tech Stack

| Layer       | Tech                               |
|------------|-------------------------------------|
| Frontend   | React, Tailwind CSS, Vite, Axios    |
| Admin      | React, Tailwind CSS, Vite           |
| Backend    | Node.js, Express, MongoDB, Mongoose |
| Auth       | JWT (JSON Web Tokens)               |
| Deployment | Vercel (frontend/admin), Render     |

---

## ✨ Features

✔️ Doctor & patient authentication  
✔️ Admin panel to manage doctors, appointments  
✔️ Patient dashboard to book and view slots  
✔️ Responsive UI with Tailwind CSS  
✔️ Backend API for all CRUD operations  
✔️ Environment-based config via `.env`  
✔️ Deployment-ready (vercel.json included)

---

## 🛠️ Setup Instructions

1. Clone the repo:

git clone https://github.com/yourusername/prescripto.git
cd prescripto

2.	Install dependencies:

  cd backend && npm install
  cd ../frontend && npm install
  cd ../admin && npm install

3.	Set up environment:

  Create a .env file in backend folder:
  PORT=4000
  MONGO_URI=mongodb+srv://<your-mongodb-uri>
  JWT_SECRET=yourSecret

---

## 🛠 Technologies Used:

	•	Node.js
	•	Express.js
	•	MongoDB (via Mongoose)
	•	JWT (Authentication)
	•	Dotenv, CORS, Middleware
---

## 📁 Project Structure

mediConnect/
├── frontend/  🔹 Patient/User-facing React App
│   ├── public/
│   ├── src/
│   │   ├── assets/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── services/ (Axios API calls)
│   │   ├── App.jsx
│   │   └── main.jsx
│   ├── vite.config.js
│   └── tailwind.config.js

├── admin/  🔹 Admin Panel React App
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── services/
│   │   ├── App.jsx
│   │   └── main.jsx
│   ├── vite.config.js
│   └── tailwind.config.js

├── backend/  🔹 Node.js + Express API
│   ├── config/ (e.g., DB connection)
│   ├── controllers/ (logic for routes)
│   ├── middleware/ (JWT, error handling)
│   ├── models/ (Mongoose schemas)
│   ├── routes/
│   ├── utils/
│   ├── .env
│   ├── server.js
│   └── package.json

└── README.md 📝

---

## 👨‍💻 Team Collaboration
  Apurva Palwe
  Yash Marke
---
## 📣 Feedback:
If you found this helpful, give it a ⭐ on GitHub. Your support motivates us!
