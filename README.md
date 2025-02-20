Here's the modified README with your admin feature and customer booking system included:

---

# Hotel Management System

## About
Hotel Management System is a web application developed using **Spring Boot**, **MySQL**, **JPA**, and **Thymeleaf**, deployed on **Tomcat Server**. The system is designed to handle various hotel management functions efficiently and is user-friendly for both administrators and customers. Developed an admin feature for managing reservations and hotel services, allowing customers to book rooms, check availability, and cancel reservations online.

## Features
- Built using **Spring Boot** for rapid development.
- Uses **MySQL** as the database for storing records.
- **Thymeleaf** for dynamic and interactive web pages.
- Organized into the following modules:
  - **Booking**: Manages hotel room reservations, allows customers to book rooms, view availability, and cancel reservations online.
  - **Check-In**: Handles guest check-in processes.
  - **Check-Out**: Manages guest check-out and billing transactions.
  - **Restaurant**: Manages restaurant menus and transactions.
  - **Services**: Tracks additional services provided to guests.
  - **Queue Management**: Organizes restaurant and hotel service queues.
  - **Users**: Handles system users and authentication.
  - **Admin**: Allows administrators to manage reservations and hotel services.

## Prerequisites
- **Java 16**
- **Maven** (for dependency management)
- **MySQL Database**
- **Tomcat Server**

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/your-repo/hotel-management-system.git
   cd hotel-management-system
   ```
2. Configure the MySQL database in `application.properties`:
   ```properties
   spring.datasource.url=jdbc:mysql://localhost:3306/hotel_db
   spring.datasource.username=root
   spring.datasource.password=yourpassword
   ```
3. Build and run the application:
   ```sh
   mvn spring-boot:run
   ```
4. Access the application in the browser at:
   ``` 
   http://localhost:8080
   ```

## Technologies Used
- **Spring Boot**
- **MySQL**
- **JPA & JDBC**
- **Thymeleaf**
- **Bootstrap & jQuery** (for frontend styling and interaction)

## License
This project is open-source and available under the [MIT License](LICENSE).

--- 

This version includes the admin feature and the ability for customers to book, view availability, and cancel reservations.
