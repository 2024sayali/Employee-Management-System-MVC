Employee Management System

A **Java-based web application** built using **Servlets, JSP, JDBC, and MySQL**, designed to manage employee records efficiently.  
This project follows the **MVC architecture** to ensure modularity, maintainability, and clean separation of concerns.

## Features
- Admin Login System— Secure admin authentication.
- Add Employee — Admin can add new employee details.
- View Employees — Displays all employee records in a styled table.
- Edit / Update Employee — Admin can modify employee salary details.
- Delete Employee — Remove employee data from the system.
- Employee Account Creation — Employees can register and log in to their own profiles.
- Session Management — Ensures secure access for logged-in admins and employees.
- Database Integration — All data stored and retrieved from MySQL database.

## Tech Stack
| Category | Technology |
|-----------|-------------|
| **Frontend** | HTML5, CSS3 |
| **Backend** | Java (JSP, Servlets) |
| **Database** | MySQL |
| **Architecture** | MVC (Model–View–Controller) |
| **Server** | Apache Tomcat |
| **IDE** | IntelliJ IDEA / Eclipse 

## Project Structure
Employee-Management-System/
│
├── webapp/
│ ├── WEB-INF/
│ │ └── web.xml
│ │
│ ├── addemp.html
│ ├── AdminLogin.html
│ ├── EmployeeLogin.html
│ ├── EmployeeRegister.html
│ ├── index.html
│ │
│ ├── JSP/
│ │ ├── Edit.jsp
│ │ ├── EmployeeAdded.jsp
│ │ ├── Login.jsp
│ │ ├── Msg.jsp
│ │ ├── UpdateEmp.jsp
│ │ └── ViewAllEmployee.jsp
│
├── src/
│ └── main/
│ └── java/
│ └── test/
│ ├── AddEmpServlet.java
│ ├── AdminBean.java
│ ├── AdminLoginServlet.java
│ ├── DAOAddEmployee.java
│ ├── DAOAdminLogin.java
│ ├── DAODelete.java
│ ├── DAOUpdate.java
│ ├── DAOViewAllEmployee.java
│ ├── DBCon.java
│ ├── DeleteServlet.java
│ ├── EditServlet.java
│ ├── EmployeeBean.java
│ ├── EmployeeDAO.java
│ ├── LogoutServlet.java
│ ├── RegisterServlet.java
│ ├── UpdateEmpServlet.java
│ └── ViewEmpServlet.java
