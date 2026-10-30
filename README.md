# FestIQ – Smart College Fest Management System

## Project Overview
FestIQ is a web-based college fest management system developed using Spring Boot. It helps manage college fests, participant registrations, QR code generation, and attendance tracking in one application.

The system stores fest and participant information in a MySQL database. Each participant receives a unique registration code and a QR code that can be used for attendance verification.

## Objectives
- To simplify college fest management.
- To maintain fest details digitally.
- To register participants and generate unique registration codes.
- To generate QR codes for participants.
- To manage and record participant attendance.

## Features
- **Fest Management:** Create and manage college fest details.
- **Participant Registration:** Register participants and save their information.
- **Unique Registration Code:** Assign a unique registration code to each participant.
- **QR Code Generation:** Generate QR codes for participant registration.
- **Attendance Management:** Record and manage participant check-in details.
- **Database Storage:** Store fest, participant, and attendance records in MySQL.

## Technologies Used
- Java
- Spring Boot
- Spring Data JPA
- Hibernate
- MySQL
- Maven
- Thymeleaf and HTML
- ZXing library for QR code generation

## Database
The application uses MySQL with the following tables:

- `fest` – Stores fest details.
- `participant` – Stores participant registration details.
- `attendance` – Stores attendance and check-in records.

## Requirements
- Java Development Kit (JDK)
- Apache Maven
- MySQL Server
- NetBeans IDE or another Java IDE

## How to Run the Project
1. Clone or download this repository.
2. Open the project in NetBeans or another compatible IDE.
3. Create the MySQL database named `smart_college_fest`.
4. Configure the database connection in `src/main/resources/application.properties`.
5. Ensure the required Maven dependencies are downloaded.
6. Run the Spring Boot application.
7. Open the application in your web browser using the local address and port configured by the project.

## Project Purpose
This project was developed as an academic mini project to demonstrate the use of Spring Boot, database connectivity, participant registration, QR code generation, and attendance management in a college fest environment.

## Author
**Janvi Rana**  
MCA (Data Science)  
Chandigarh University
