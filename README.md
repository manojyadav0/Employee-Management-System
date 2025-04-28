# Employee Management System

A simple **Java Swing**-based Employee Management System application with **MySQL** database connectivity.

---

## 📚 Overview

This Employee Management System allows users to:

- Add a new employee
- View all employee details
- Update an existing employee
- Remove an employee
- Login securely with a username and password

It provides a clean GUI interface built with **Java Swing** and connects to a **MySQL** database to store and manage employee data.

---

## ✨ Features

- Login Authentication for system security
- Splash Screen introduction
- CRUD Operations (Create, Read, Update, Delete)
- Search Employee by ID
- Print Employee Details from the view screen
- Database Connectivity using JDBC

---

## 🛠️ Technologies Used

- Java (Swing, AWT)
- MySQL (Database)
- JDBC (Java Database Connectivity)

**Libraries:**
- `com.toedter.calendar.JDateChooser`
- `net.proteanit.sql.DbUtils` (for displaying result sets in JTable)

---

## 📁 Project Structure

- `Splash.java` – Welcome screen with blinking heading
- `Login.java` – User authentication
- `Home.java` – Main dashboard with navigation options
- `AddEmployee.java` – Add new employee information
- `ViewEmployee.java` – View/search/print employee records
- `UpdateEmployee.java` – Update employee details
- `RemoveEmployee.java` – Delete employee record
- `Conn.java` – Database connection setup

---

## ⚙️ Setup Instructions

### 1. Clone this repository:
```bash
git clone https://github.com/yourusername/employee-management-system.git
cd employee-management-system
