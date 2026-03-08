# 🧑‍💻 Employee Management System

![Java](https://img.shields.io/badge/Language-Java-blue)
![Project Type](https://img.shields.io/badge/Project-Console%20Application-green)
![Status](https://img.shields.io/badge/Status-Completed-success)

A **Java console-based Employee Management System** designed to manage employee records efficiently using **Java Collections and File Handling**.

This project demonstrates the use of:

* Object-Oriented Programming (OOP)
* Java Collections Framework
* File handling using serialization
* Modular program design

---

# 📖 Project Overview

The **Employee Management System (EMS)** is a menu-driven Java application that helps manage employee data in an organized and efficient manner.

The system allows users to:

* Store employee details
* Search employees quickly
* Generate employee reports
* Save and load employee data

Employee data is stored using **ArrayList** and **HashMap**, providing efficient storage and fast lookup operations.

---

# ✨ Features

| Feature            | Description                                 |
| ------------------ | ------------------------------------------- |
| ➕ Add Employee     | Add new employee records                    |
| 📋 View Employees  | Display all employee details                |
| 🔍 Search Employee | Search employees by ID, name, or department |
| ✏ Update Employee  | Modify employee information                 |
| ❌ Delete Employee  | Remove employee from system                 |
| 📊 Reports         | Generate salary statistics and summaries    |
| 💾 Save Data       | Save employee data to file                  |
| 📂 Load Data       | Load employee data from file                |

---

# 🏗 Project Structure

```
EmployeeManagementSystem
│
├── Employee.java
├── EmployeeManagementSystem.java
├── EmployeeFileHandler.java
├── EmployeeReportGenerator.java
│
├── employees.dat
└── README.md
```

### File Description

| File                            | Purpose                               |
| ------------------------------- | ------------------------------------- |
| `Employee.java`                 | Employee data model                   |
| `EmployeeManagementSystem.java` | Main program with menu and operations |
| `EmployeeFileHandler.java`      | Handles saving and loading data       |
| `EmployeeReportGenerator.java`  | Generates reports and statistics      |

---

# ⚙️ Setup Instructions

Follow these steps to run the project on your system.

---

## 1️⃣ Install Java

Make sure Java is installed.

Check version:

```bash
java -version
```

---

## 2️⃣ Clone the Repository

```bash
git clone https://github.com/yourusername/employee-management-system.git
```

---

## 3️⃣ Open Project Folder

```bash
cd employee-management-system
```

---

## 4️⃣ Compile the Program

```bash
javac *.java
```

---

## 5️⃣ Run the Application

```bash
java EmployeeManagementSystem
```

---

# 🖥 Application Menu

When the program starts, the following menu appears:

```
=== EMPLOYEE MANAGEMENT SYSTEM ===

1. Add New Employee
2. View All Employees
3. Search Employee
4. Update Employee
5. Delete Employee
6. Generate Reports
7. Save to File
8. Load from File
9. Exit
```

Users can select options to perform employee management tasks.

---

# 💾 Data Storage

Employee data is stored using **Java Serialization**.

File created:

```
employees.dat
```

This file stores:

```
ArrayList<Employee>
```

Each employee record contains:

* Employee ID
* Name
* Department
* Position
* Salary
* Join Date

---

# 🧪 Testing

The application was tested using multiple scenarios:

| Test Case | Operation              | Result   |
| --------- | ---------------------- | -------- |
| TC1       | Add Employee           | ✅ Passed |
| TC2       | View Employees         | ✅ Passed |
| TC3       | Search Employee        | ✅ Passed |
| TC4       | Generate Salary Report | ✅ Passed |
| TC5       | Save/Load Data         | ✅ Passed |

---

# 📚 Learning Outcomes

Through this project, the following concepts were practiced:

* Java OOP principles
* Java Collections (ArrayList & HashMap)
* File handling with serialization
* Exception handling
* Modular programming

---

# 👨‍💻 Author

**Rajat Kumar**

---
