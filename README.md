# Crime Management System

## Overview
The **Crime Management System** is a web-based application that facilitates online complaint registration and computerized management of crime records. It enables users to file complaints online, which are then received by the police. The police can track and manage crime records efficiently through this system, reducing paperwork and manual processes.

## Features
- **User Registration & Authentication**: Users must register before filing complaints.
- **Complaint Management**: Citizens can register complaints, track their status, and receive updates from the police.
- **Criminal Records Management**: Store and manage criminal records for law enforcement.
- **Police Database Management**: Secure storage of police personnel details.
- **Admin Dashboard**: Allows administrators to manage master data, remove outdated records, and oversee system operations.
- **Public Information**: News, safety tips, missing persons, and most wanted criminals can be accessed without logging in.

## Technologies Used
- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Java, Spring Boot
- **Database**: MySQL
- **Frameworks**: Spring Boot for backend services

## Modules
### 1. Station Module
- Police stations register on the platform and access existing crime records.

### 2. Citizen Module
- Users register, log in, and submit complaints.
- Users receive complaint status updates.

### 3. Crime Module
- Input and manage details related to crimes.

### 4. Admin Module
- Manages master data, removes outdated records, and oversees system operations.

## System Design
- **System Flow Diagram**: Illustrates the interaction between users, police, and administrators.
- **Use Case Diagrams**: Represents functionalities for different actors like Citizens, Police, and Admins.

## Snapshots
- **Admin Sign-in Page**: Secure login for administrators.
- **Application Homepage**: Central hub for users.
- **Add Criminal Page**: Enables authorized users to add new criminal records.
- **Edit Criminal Record Page**: Allows modification of existing records.
- **Admin Signup Page**: Interface for administrator registration.

## Advantages
- Reduces time consumption.
- Eliminates paperwork.
- Prevents record loss.
- Centralized database management.

## Future Scope
- Multi-language support.
- Improved graphics and UI.
- Cloud-based document version management.

## Installation Guide
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/crime-management-system.git
   ```
2. Navigate to the project directory:
   ```sh
   cd crime-management-system
   ```
3. Install dependencies and configure the database:
   ```sh
   mvn install
   ```
4. Run the application:
   ```sh
   mvn spring-boot:run
   ```

## Contributors
- **M. Mathesh** - mm8715@srmist.edu.in
- **K. John Ebin Kiruba** - jk3994@srmist.edu.in
- **C. Saravana** - sc9240@srmist.edu.in

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
