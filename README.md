🎓 Student Attendance Management System

A full-stack web application to manage and track student attendance efficiently. Built with Node.js, Express.js, and MySQL, and deployed live on Railway.

🔗 Live Demo: student-attendance-system-production-987f.up.railway.app


📌 Features


🔐 Secure login system for authorized access
📝 Mark and record daily student attendance
📊 View complete attendance history
🔄 Reset attendance records when needed
💾 Persistent data storage using MySQL
☁️ Fully deployed on the cloud (Railway)



🛠️ Tech Stack

Frontend:


HTML5
CSS3
JavaScript (Vanilla)


Backend:


Node.js
Express.js


Database:


MySQL


Deployment:


Railway (Cloud Hosting + MySQL Database)



📂 Project Structure

Student-Attendance-System/
├── login.html                 # Login page
├── dashboard.html              # Main dashboard
├── attendance.html             # Mark attendance page
├── attendance-history.html     # View attendance history
├── server.js                   # Express server & API routes
├── package.json                 # Project dependencies
└── README.md


⚙️ Installation & Setup (Run Locally)


Clone the repository


bash   git clone https://github.com/sangavis109-crypto/Student-Attendance-System.git
   cd Student-Attendance-System


Install dependencies


bash   npm install


Set up MySQL Database

Create a database named attendance_system
Import the required tables (students, attendance)



Configure environment variables
Create a .env file or set the following variables:


   MYSQLHOST=localhost
   MYSQLUSER=root
   MYSQLPASSWORD=your_password
   MYSQLDATABASE=attendance_system
   MYSQLPORT=3306


Run the application


bash   node server.js


Visit http://localhost:3000 in your browser.



🌐 Deployment

This project is deployed using Railway:


Node.js app and MySQL database hosted as separate services
Environment variables securely managed via Railway's dashboard
Automatic deployments triggered on every GitHub push



🚀 Future Improvements


Add role-based access (Admin/Teacher/Student)
Export attendance reports as PDF/Excel
Add email notifications for absentees
Implement password hashing for enhanced security



👩‍💻 Author

Sangavi S


GitHub: @sangavis109-crypto



⭐ If you found this project helpful, consider giving it a star!
