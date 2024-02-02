# JPA-Hibernate-advanced-Mapping-
Developed a Spring Boot application with advanced mapping capabilities using Spring Data JPA and Hibernate.  
Mmanaged intricate relationships among instructors, courses, Reviews ,and students within a MySQL database, demonstrating proficiency in relational database design

#### Technologies Used:

- **Java:** Leveraged the power of Java for building a robust and scalable backend.
- **Spring Boot:** Utilized Spring Boot to expedite the development process and create a standalone, production-ready application.
- **Spring Data JPA:** Utilizes Spring Data JPA for simplified data access and management.
- **JPA:** Integrated Java Persistence API for seamless interaction with the MySQL database.
- **MySQL:** Utilized MySQL as the relational database for storing and managing employee information.

## Installation

### Prerequisites

- Java Development Kit (JDK)
- MySQL Database
- MySQL Workbench

### Setup

1. Clone the repository: `git clone https://github.com/your-username/employee-management.git`
2. Create a new database in MySQL Workbench:
   - Open MySQL Workbench and connect to your MySQL Server.
   - Run the SQL script provided in this directory `JPA-Hibernate-advanced-Mapping/sql-scripts` to create the necessary database and tables.

3. Update application.properties:
   - Open `src/main/resources/application.properties`.
   - Modify the database connection properties based on your MySQL setup.
      `spring.datasource.url=jdbc:mysql://localhost:3306/hb-05-many-to-many`
      `spring.datasource.username={your username}`
      `spring.datasource.password={your password}`

4. Run the application.

The application will be accessible at [http://localhost:8080](http://localhost:8080).
