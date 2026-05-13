Employee Management System

A full-stack web application built with Spring Boot, Thymeleaf, Spring Data JPA, and MySQL that allows you to manage employee records with full CRUD functionality.

Features -> 

View all employees on the home page,

Add a new employee

Update existing employee details

Delete an employee

Tech Stack ->

Layer         -        Technology

Backend       -        Spring Boot 4.0.6

Frontend      -        Thymeleaf

Persistence   -        Spring Data JPA (Hibernate)

Database      -        MySQLBuild 

Tool          -        Maven

Java Version  -        Java 17 

Project Structure
employee-management-system/
├── src/
│   └── main/
│       ├── java/com/employee/
│       │   ├── EmployeeManagementSystemApplication.java   # Main entry point
│       │   ├── controller/
│       │   │   └── EmployeeController.java                # MVC Controller
│       │   ├── model/
│       │   │   └── Employee.java                          # JPA Entity
│       │   ├── repository/
│       │   │   └── EmployeeRepository.java                # JPA Repository
│       │   └── service/
│       │       ├── EmployeeService.java                   # Service Interface
│       │       └── EmployeeServiceImpl.java               # Service Implementation
│       └── resources/
│           ├── templates/                                 # Thymeleaf HTML templates
│           └── application.properties                     # App configuration
├── pom.xml
└── README.md

API Endpoints
MethodURLDescriptionGET/View all employeesGET/addShow add employee formPOST/saveSave a new employeeGET/updateform/{id}Show update form by IDGET/delete/{id}Delete employee by ID

📦 Employee Model
FieldTypeDescriptionidlongAuto-generated primary keynameStringEmployee full nameemailStringEmployee email addressageStringEmployee agedesignationStringJob title/designation
