# Employee Management System

A Spring Boot REST API project for managing employee records.  
This application provides CRUD operations to create, read, update, and delete employee information using RESTful web services.

---

## 🚀 Features
- Add new employees
- View all employees
- Get employee by ID
- Update employee details
- Delete employee
- RESTful API design
- Proper exception handling
- JSON-based request & response

---

## 🛠️ Tech Stack
- **Backend:** Java 17
- **Framework:** Spring Boot
- **ORM:** Hibernate / JPA
- **Database:** MySQL
- **Build Tool:** Maven
- **API Testing:** Postman
- **Version Control:** Git & GitHub

---

## 📂 Project Structure
employee-management-system
│
├── src/main/java
│ ├── com.employee.controller
│ ├── com.employee.service
│ ├── com.employee.repository
│ ├── com.employee.entity
│
├── src/main/resources
│ └── application.properties
│
├── pom.xml
└── README.md


---

## 🔗 REST API Endpoints

### ➕ Create Employee
**POST** `/api/employees`

```json
{
  "name": "Arun",
  "email": "arun@gmail.com",
  "department": "IT",
  "salary": 45000
}

📄 Get All Employees

GET /api/employees

🔍 Get Employee by ID

GET /api/employees/{id}

✏️ Update Employee

PUT /api/employees/{id}

{
  "name": "Arun Kumar",
  "email": "arun@gmail.com",
  "department": "HR",
  "salary": 50000
}

❌ Delete Employee

DELETE /api/employees/{id}

⚙️ How to Run the Project

Clone the repository

git clone https://github.com/shamiha007/employee-management-system.git


Import the project into Spring Tool Suite / Eclipse

Configure MySQL in application.properties

spring.datasource.url=jdbc:mysql://localhost:3306/employee_db
spring.datasource.username=root
spring.datasource.password=your_password


Run the application as Spring Boot App

Test APIs using Postman

http://localhost:8080/api/employees

📌 Learning Outcomes

Hands-on experience with Spring Boot REST APIs

CRUD operations using Hibernate & JPA

API testing using Postman

GitHub version control workflow

Real-world backend project structure

👩‍💻 Author

Shamiha Sherin
GitHub: https://github.com/shamiha007
