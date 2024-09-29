# Employee Management System

## Overview

The Employee Management System is a web application built with Spring Boot 3, Spring MVC, Thymeleaf, and MySQL. This application allows users to manage employee records, including adding, updating, viewing, and deleting employee information.

## Features

  
- **CRUD Operations**: Users can easily create, read, update, and delete employee records, allowing for efficient management of employee data.
  
- **Pagination**: The application implements pagination and sorting for employee listings, enabling users to navigate through large datasets effortlessly. This feature enhances performance and improves user experience by loading data in manageable chunks.
  
- **Responsive UI**: The application utilizes Thymeleaf for dynamic web page rendering, ensuring that the interface is intuitive and responsive across different devices.
  
- **MySQL Integration**: Employee data is stored in a MySQL database, providing a reliable and structured environment for data persistence.

## Technologies Used

- **Java**: Version 17+
- **Spring Boot**: 3.x
- **Spring MVC**: 6.x
- **Thymeleaf**: For rendering dynamic web pages
- **MySQL**: Database for storing employee data

## Prerequisites

- JDK 17 or higher
- Maven 3.x
- MySQL Server
- IDE (e.g., IntelliJ IDEA, Eclipse)

## Required Dependencies


1. **Spring Web**
   - **Type**: WEB
   - **Description**: Build web applications, including RESTful applications, using Spring MVC. Uses Apache Tomcat as the default embedded container.

2. **Thymeleaf**
   - **Type**: TEMPLATE ENGINES
   - **Description**: A modern server-side Java template engine for both web and standalone environments. Allows HTML to be correctly displayed in browsers and as static prototypes.

3. **MySQL Driver**
   - **Type**: SQL
   - **Description**: MySQL JDBC driver for database connectivity.

4. **Spring Data JPA**
   - **Type**: SQL
   - **Description**: Persist data in SQL stores with Java Persistence API using Spring Data and Hibernate.


## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Aakash995/employee_management_system.git
   cd employee_management_system
   
2. Configure the Database: I have configured the database configuration using .yml file. Update the application.yml file with your database credentials.

3. Screenshots of the project:

   1. Employee Lists:
   
     ![image](https://github.com/user-attachments/assets/c2de0bfa-de91-43c6-a002-00b27826c49b)

  2. Add Employee:
     
   ![image](https://github.com/user-attachments/assets/90bbff25-d28a-45b5-91ce-49ffb7c9b89a)

3. Edit Employee Details:

   ![image](https://github.com/user-attachments/assets/3be893f9-2167-43e2-83e6-feaf3246b523)
   
4. Pagination Support:
  
  - First Page:  ![image](https://github.com/user-attachments/assets/fd02a389-4c1e-4539-806c-2fe288c20da4)
  - 2nd / Next Page: ![image](https://github.com/user-attachments/assets/f36a530b-8393-48a2-b3b0-a566f23ad70b)

5. Sorting feature based on first name, last name and email:

   - Ascending order by first name: ![image](https://github.com/user-attachments/assets/579171f7-12ef-4795-86fd-bd85b895dfd9)
   - Descending order by last name: ![image](https://github.com/user-attachments/assets/aa359110-fa16-4af6-8c12-b32e888b27e3)

