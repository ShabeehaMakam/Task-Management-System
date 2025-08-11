# Task Management System

A simple role-based task management web application where:
- **Admin** can create projects and assign them to managers.
- **Manager** can view assigned projects and create tasks for employees.
- **Employee** can view tasks and send feedback/messages to the manager.

---

## 🚀 Features

### 👩‍💼 Admin
- Add new projects with details.
- Assign projects to managers.
- View, edit, and delete project details.

### 👨‍💼 Manager
- View assigned projects.
- Add tasks for employees.
- View employee feedback/messages.

### 👷 Employee
- View all tasks assigned to them.
- Cannot edit or delete tasks.
- Send messages/feedback to manager.

---

## 📂 Project Structure

project-root/
│
├── db_connect.php # Database connection
├── index.php # Main dashboard / routing
├── pages/
│ ├── projects/ # Project-related pages
│ ├── tasks/ # Task management pages
│ └── messages/ # Employee feedback pages
├── assets/
│ ├── css/ # Stylesheets
│ ├── js/ # JavaScript files
│ └── images/ # Project images
├── sql/
│ └── tmsdb.sql # Database schema & sample data
└── README.md # Project documentation

yaml
Copy
Edit

---

## 🛠️ Technologies Used
- **Frontend:** HTML, CSS, JavaScript, Bootstrap
- **Backend:** PHP
- **Database:** MySQL

---

## ⚙️ Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/ShabeehaMakam/task-management-system.git
Move the project to your XAMPP/htdocs folder

bash
Copy
Edit
C:/xampp/htdocs/task-management-system
Import the Database

Open phpMyAdmin.

Create a new database (tmsdb).

Import the file: sql/tmsdb.sql.

Update Database Connection

Open db_connect.php and update:

php
Copy
Edit
$conn = new mysqli("localhost", "root", "", "tmsdb");
Run the Project

Start Apache & MySQL in XAMPP.

Go to: http://localhost/task-management-system

🔐 Default Login Credentials
Role	Username	Password
Admin	admin@gmail.com	admin123
Manager	manager@example.com	manager123(can create by new project manager)
Employee	employee@example.com	employee123 (can create by new employee)

📌 Notes
Make sure you have PHP ≥ 7.4 and MySQL ≥ 5.7 installed.

Bootstrap & Font Awesome are included for UI styling.

📜 License
This project is open-source and free to use for educational purposes.

yaml
Copy
Edit

---

Do you want me to **add screenshots and sample database schema diagrams** into this README so it looks more professional?  
That will make it easier for anyone to understand the project at a glance.
