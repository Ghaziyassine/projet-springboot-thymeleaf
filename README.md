# projet-springboot-thymeleaf
# Employee and Machine Management System
## Table des matières

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [ScreenShots ](#screenShots)
- [Usage](#usage)
- [Contributing](#contributing)
  

## Description

This project aims to develop a simple application for assigning machines to employees. The application will be built using Thymeleaf and Spring Boot.

### Features

1. **CRUD Operations:**
   - Manage employees and machines with Create, Read, Update, and Delete operations.

2. **Filter Machines Lsit by Employee:**
   - Search for machines assigned to a specific employee.

3. **Graphical Representation:**
   - View a graph illustrating the number of machines aquired per year.




## Technologies Used

**Backend:**

- Java with Spring Boot (MVC)
- Spring Data JPA for data access
- Thymeleaf for server-side templating

**Frontend:**

- HTML,css,javascript
- Thymeleaf for server-side templating
- Chart.js for creating charts
**Database:**
- Msql


## Project Configuration

Before modifying `persistence.xml` and `glassfish-resources.xml`, ensure that the JDBC pool and JDBC resources are configured in GlassFish.

### JDBC Pool Configuration (example):

- Pool Name: `YourPoolName`
- Resource Type: `java.sql.Driver`
- Driver Classname: `com.mysql.jdbc.Driver`
- Additional Properties: 
  - `user = your-mysql-username`
  - `password = your-mysql-password`
  - `databaseName = your-database-name`
  - `portNumber = your-mysql-port`
  - `Url = jdbc:mysql://your-mysql-host:your-mysql-port/your-database-name`

### JDBC Resource Configuration (example):

- JNDI Name: `jdbc/YourDataSource`
- Pool Name: `YourPoolName`

## ScreenShots 





## Authors

- Mohamed Fezzazi ([MaskedFezz](https://github.com/MaskedFezz))
- Ghita Baghdad ([ghita-baghdad](https://github.com/ghita-baghdad))
- Yassine Ghazi ([Ghaziyassine](https://github.com/Ghaziyassine))
