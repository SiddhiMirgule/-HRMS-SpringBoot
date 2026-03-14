#HRMS – Human Resource Management System

Project Description:
HRMS is a Spring Boot-based web service application designed to manage job postings, employer and candidate information, and job applications. The project demonstrates modern backend development practices, including REST API design, DTOs, validation, global exception handling, and layered architecture.

Key Features:

City Management: Add and list cities.

Job Position Management: Add and list job positions.

Employer Management: Register and list employers.

Candidate Management: Register and list job seekers.

Job Advertisement Management: Add, list, and filter job ads.

Job Application Management: Allow candidates to apply for job ads.

Validation: Field validation using annotations like @NotBlank and @Size.

Error Handling: Global exception handling with @ControllerAdvice.

Tech Stack:

Backend: Java 17, Spring Boot, Spring Data JPA (Hibernate)

Database: PostgreSQL

Utilities: Lombok, Validation API, Jackson

API Testing: Postman

Project Architecture / Layers:

Entity: Represents database tables

DTO / Request: Data transfer and request objects

Service: Business logic layer

Repository (DAO): Database access layer

Controller: REST API endpoints

Core Utilities: Result, DataResult, SuccessResult, ErrorResult for standardized responses

Sample API Endpoints:

POST /api/employers/register – Register a new employer

GET /api/employers/getAll – List all employers

POST /api/candidateController/register – Register a new candidate

POST /api/jobAdvertisements/add – Add a new job advertisement

POST /api/jobApplications/apply – Apply for a job

Skills Demonstrated:

Spring Boot backend development

RESTful API design and integration

Database design and CRUD operations with PostgreSQL

Validation and global exception handling

Layered architecture (Controller → Service → Repository)

Use Cases:

HR departments can manage job postings, candidates, and applications efficiently

Practice project for full-stack Java developers

Demonstrates enterprise-level backend development skills
