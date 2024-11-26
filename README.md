## JOB PORTAL APPLICATION

A web-based job portal application built with Java 23 and Spring Boot. This project allows users to search for jobs, apply for positions, and manage job postings.

## Features

User registration and authentication

Two types of login:

Job Seeker: Can search for jobs and apply to positions

Recruiter: Can post job listings and manage applications

Job search functionality

Job application submission

Admin management for job postings

## Prerequisites
Java 23 or above

Spring Boot 3.x.x (Latest version)

Maven (for managing dependencies)

## MySQL database

Setup
1. Clone the repository:

 git clone https://github.com/yourusername/job-portal.git

2. Configure the database connection in src/main/resources/application.properties:

spring.datasource.url=jdbc:mysql://localhost:3306/job_portal

spring.datasource.username=your_db_username

spring.datasource.password=your_db_password

spring.jpa.hibernate.ddl-auto=update

Replace your_db_username and your_db_password with your database credentials.

3. Run Sql code in your database given in this repository

4. Build and run the application:

mvn spring-boot:run

