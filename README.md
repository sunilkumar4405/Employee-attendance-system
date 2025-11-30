# Employee-Attendance-System
CH SUNIL KUMAR
VIGNANS LARA INSTITUTE OF TECHNOLOGY AND SCIENCE(B.TECH-CSD)
CONTACT NO:7674935014

A secure MERN-based Employee Attendance System that uses IP validation to ensure authentic logins and prevent proxy attendance marking.
The Employee Attendance System is a full-stack web application built with the MERN (MongoDB, Express, React, Node.js) stack.
This system helps organizations track employee attendance, working hours, and provides role-based dashboards for both Employees and Managers.

🚀 Features
👨‍🏫 Employee Features

Register & Login

Secure token-based authentication (JWT)

Mark Check-In & Check-Out

Prevent multiple check-ins per day

View personal attendance history (Table/Calendar view)

Profile management

👨‍💼 Manager/Admin Features

Login & secure role-based access

View all employees' attendance

Filter by date, employee, department

Export attendance reports

Manage employees data

🛠️ Tech Stack
Frontend

React.js

Redux Toolkit or Zustand

TailwindCSS / Material UI

Backend

Node.js

Express.js

JSON Web Token (JWT)

Bcrypt.js (password hashing)

Database

MongoDB Atlas (Cloud Database)

Mongoose ODM

📁 Project Structure
Employee-Attendance-System/
│
├── client/               # React frontend
│   ├── src/
│   ├── components/
│   ├── pages/
│   ├── redux/ or zustand/
│   └── ...
│
├── server/               # Node.js backend
│   ├── models/           # Mongoose schemas
│   ├── routes/           # API routes
│   ├── middleware/       # Auth middleware
│   ├── controllers/      # API logic
│   ├── server.js         # Main server file
│   └── ...
│
└── README.md

🔗 API Endpoints
🔐 Authentication
Method	Endpoint	Description
POST	/api/auth/register	Register new employee
POST	/api/auth/login	Login & get JWT token
🧑‍💼 Employee Attendance
Method	Endpoint	Description
POST	/api/attendance/checkin	Mark check-in
POST	/api/attendance/checkout	Mark check-out
GET	/api/attendance/my	Get personal attendance
👨‍💼 Manager/Admin
Method	Endpoint	Description
GET	/api/attendance/all	View all employees attendance
GET	/api/employees	Fetch all employees
⚙️ Installation & Setup
1️⃣ Clone the repository
git clone https://github.com/your-username/Employee-Attendance-System.git

2️⃣ Install server dependencies
cd server
npm install

3️⃣ Install client dependencies
cd client
npm install

🔧 Environment Variables

Create .env inside the server folder:

PORT=10000
MONGO_USER=your_db_user
MONGO_PASS=your_db_password
MONGO_CLUSTER=your_cluster.mongodb.net
MONGO_DB=attendance_db
JWT_SECRET=your_secret_key

▶️ Running the Application
Start backend
cd server
npm start

Start frontend
cd client
npm start


Frontend runs on:
👉 http://localhost:3000

Backend runs on:
👉 http://localhost:10000

🛡️ Security Features

Password hashing using bcrypt

JWT based authentication

Protected routes for Employees & Managers

Role-based authorization

Validation using middleware

📊 Future Enhancements

Add biometric scanner or QR-based attendance

Export attendance PDF & Excel

Leave management system

Email notifications for late check-ins

Mobile responsive design

Admin dashboard analytics

📝 License

This project is open-source. You can modify and use it freely for learning or organizational needs.

CH SUNIL KUMAR
VIGNANS LARA INSTITUTE OF TECHNOLOGY AND SCIENCE(B.TECH-CSD)
CONTACT NO:7674935014

