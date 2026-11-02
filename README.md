# Student Record System Using Oracle PL/SQL

## 📌 Project Overview

The **Student Record System** is a database management project developed using Oracle Database and PL/SQL, with a Python Flask backend and a simple web-based frontend.

The main purpose of this project is to manage student information efficiently. It allows users to store, view, update, search, and delete student records in an organized manner.

## 🎯 Objectives

- To develop an efficient student record management system.
- To understand Oracle Database connectivity with Python.
- To implement database operations using SQL and PL/SQL.
- To perform CRUD operations on student records.
- To provide a simple and user-friendly interface for managing student information.

## 🛠️ Technologies Used

- **Database:** Oracle Database
- **Database Programming:** SQL and PL/SQL
- **Backend:** Python (Flask)
- **Frontend:** HTML, CSS, JavaScript
- **Database Connectivity:** Python Oracle Driver (oracledb)
- **Development Environment:** Visual Studio Code

## ✨ Features

- Add new student records.
- View all registered student records.
- Update existing student information.
- Delete student records.
- Store student details securely in Oracle Database.
- Connect the web application with Oracle Database.
- Perform database operations through a user-friendly interface.

## 📂 Project Structure

```text
Student-Record-System/
│
├── app.py
├── index.html
├── student_record.sql
├── requirements.txt
└── README.md
```

## ⚙️ Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/YourUsername/student-record-system-oracle-plsql.git
```

### 2. Open the Project Folder

```bash
cd student-record-system-oracle-plsql
```

### 3. Install Required Dependencies

```bash
pip install -r requirements.txt
```

### 4. Configure Oracle Database

Set the following environment variables according to your Oracle Database configuration:

```powershell
$env:ORACLE_USER="your_username"
$env:ORACLE_PASSWORD="your_password"
$env:ORACLE_DSN="localhost:1521/XEPDB1"
```

### 5. Create the Database Table

Execute the `student_record.sql` file in Oracle SQL Developer or another Oracle SQL environment.

### 6. Run the Flask Application

```bash
python app.py
```

Open the application in your browser using the local URL displayed in the Flask terminal.

## 📚 Learning Outcomes

- Understanding Oracle Database and PL/SQL.
- Learning database connectivity using Python.
- Implementing CRUD operations.
- Understanding Flask backend development.
- Integrating frontend, backend, and database technologies.
- Developing a practical database management application.

## 🔮 Future Enhancements

- Student login and authentication.
- Search and filter student records.
- Generate student reports.
- Export student records to PDF or Excel.
- Add attendance and academic performance management.

## 👨‍💻 Author

**Pushveer Singh**

## 📄 License

This project is developed for educational and academic purposes.
