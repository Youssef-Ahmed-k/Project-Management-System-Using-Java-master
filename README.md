# Project Management System

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white)
![Swing](https://img.shields.io/badge/Swing-007396?style=for-the-badge&logo=java&logoColor=white)
![MSSQL](https://img.shields.io/badge/SQL%20Server-CC2927?style=for-the-badge&logo=microsoft-sql-server&logoColor=white)
![NetBeans](https://img.shields.io/badge/NetBeans-1B6AC6?style=for-the-badge&logo=apache-netbeans-ide&logoColor=white)

---

## Overview

This is a **Project Management System** built with Java (Swing) and Microsoft SQL Server. It allows organizations to manage users, projects, tasks, attendance, vacations, penalties, and reports with different roles: Admin, Project Manager, Team Leader, and Employee.

---

## Features

- **User Authentication**: Login system for Admin, Project Manager, Team Leader, and Employee.
- **User Management**: Add, update, view, and delete users (Admin).
- **Project Management**: Assign projects to team leaders and manage project progress.
- **Task Management**: Assign tasks to employees, upload completed tasks, and view assigned/completed tasks.
- **Attendance Tracking**: Employees can record attendance and exit times.
- **Vacation Requests**: Employees can request vacations; team leaders can approve or refuse.
- **Penalties**: Team leaders can assign and delete penalties.
- **Reports**: Project managers and team leaders can write and view reports.

---

## Technologies Used

- **Java (Swing)**: Desktop GUI
- **Microsoft SQL Server**: Database
- **JDBC**: Database connectivity
- **NetBeans IDE**: Development environment

---

## Project Structure

- `src/finalproject/`: Main source code (Java classes, forms, icons)
- `Database File/`: SQL Server database files (`.mdf`, `.ldf`)
- `build/`: Compiled classes and build artifacts
- `mssql-jdbc-8.4.1.jre14.jar`: JDBC driver for SQL Server

---

## Getting Started

### Prerequisites

- Java JDK 8 or higher
- NetBeans IDE (recommended) or any Java IDE
- Microsoft SQL Server
- [mssql-jdbc-8.4.1.jre14.jar](https://docs.microsoft.com/en-us/sql/connect/jdbc/download-microsoft-jdbc-driver-for-sql-server)

### Setup

1. **Clone the repository**
   ```sh
   [git clone <https://github.com/Youssef-Ahmed-k/Project-Management-System-Using-Java-master.git>
   ```

2. **Open the project in NetBeans or your preferred IDE.**

3. **Restore the Database**
   - Attach `finalproject.mdf` and `finalproject_log.ldf` to your SQL Server instance.

4. **Configure Database Connection**
   - Update the database connection settings in the code or configuration files if needed.

5. **Add JDBC Driver**
   - Add `mssql-jdbc-8.4.1.jre14.jar` to your project's libraries.

6. **Build and Run**
   - Use NetBeans or run via command line:
     ```sh
     javac -cp .;mssql-jdbc-8.4.1.jre14.jar src/finalproject/*.java
     java -cp .;mssql-jdbc-8.4.1.jre14.jar finalproject.Login
     ```



## Contact

For any questions or support, please contact:

- **Name:** Youssef Ahmed
- **Email:** youssefahmed8878@icloud.com
- **LinkedIn:** [Youssef Ahmed](https://www.linkedin.com/in/youssef-ahmed-541471342/)

---

## License

This project is licensed under the MIT License.

---

## Acknowledgements

- Java Swing Documentation
- Microsoft SQL Server Documentation
- NetBeans IDE
