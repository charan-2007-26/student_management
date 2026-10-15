🎓 Student Data Management System
A robust and secure Spring Boot web application integrated with a MySQL database designed to store, manage, and track student records efficiently.
🚀 Features
Student Onboarding: Easily add and register new students.
Data Storage: Securely store personal details, academic records, and contact information.
CRUD Operations: Full capability to Create, Read, Update, and Delete student profiles.
Search & Filter: Quick lookup functionality to find students by ID, Name, or Department.
Responsive UI: Clean interface for seamless navigation across desktop and mobile devices.
🛠️ Tech Stack
Backend: Spring Boot (Java), Spring Data JPA
Database: MySQL
Frontend: Thymeleaf, HTML/CSS, Bootstrap, 
Build Tool: Maven 
📋 Prerequisites
Before running this project, ensure you have the following installed:
Java JDK 17 or higher
MySQL Server
IDE (IntelliJ IDEA, Eclipse, or VS Code)
Maven (optional, if using command line)
⚙️ Configuration & Setup
1. Database Setup
Create a new MySQL database named student_db (or your preferred name):
sql
CREATE DATABASE student_db;
Use code with caution.
2. Configure application.properties
Update the src/main/resources/application.properties file with your MySQL credentials:
properties
spring.datasource.url=jdbc:mysql://localhost:3306/student_db?useSSL=false&serverTimezone=UTC
spring.datasource.username=YOUR_MYSQL_USERNAME
spring.datasource.password=YOUR_MYSQL_PASSWORD

# JPA/Hibernate properties
spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
spring.jpa.properties.hibernate.dialect=org.hibernate.dialect.MySQLDialect
Use code with caution.
3. Running the Application
Clone the repository and run the application using Maven:
bash
git clone https://github.com
cd student-management-system
mvn spring-boot:run
Use code with caution.
The application will start on http://localhost:2020.




Skip to previous prompt
