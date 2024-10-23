Job Portal Application
A web-based job portal application built with Java 23 and Spring Boot. This project allows users to search for jobs, apply for positions, and manage job postings.

Prerequisites

Java: Java 23 or above

Spring Boot: Version 3.x.x (Latest version)

Maven: For managing dependencies


Database Configuration
Make sure to configure the database connection in the src/main/resources/application.properties file:

properties
Copy code
spring.datasource.url=jdbc:mysql://localhost:3306/job_portal
spring.datasource.username=your_db_username
spring.datasource.password=your_db_password
spring.jpa.hibernate.ddl-auto=update
Replace your_db_username and your_db_password with your database credentials.

API Endpoints
User Registration: POST /api/users/register
Job Search: GET /api/jobs
Job Application: POST /api/jobs/{id}/apply
Admin Management: POST /api/admin/jobs
Technologies Used
Backend: Java 23, Spring Boot
Database: MySQL
Build Tool: Maven
