# taxi-service-jdbc

This is a java demo project mocking the work 
of taxi and driver control system.

Functionality: 
- registration of a new driver/user
- login/logout of previously created drivers/users
- creating, updating or deleting manufacturers, cars or drivers on jsp pages
- connection between cars and drivers
- display lists of cars, drivers or manufacturers

### Structure of the project:
- DAO layer - persistence layer that communicates with DB 
- Service layer - business logic
- Controllers - accept requests and send responses
- Views - presentation layer

![](taxi_models_diagram_mini.jpg)

### Technologies used in the project:
- Java 11
- MySQL
- Tomcat
- Maven
- HTML+CSS
- JSP
- Dependency injection

### Instructions:
- get source code or fork from GitHub
- configure util/ConnectionUtil.java with your database parameters (jdbc driver, url, username, password).
- create DB schema with resources/init_db.sql file
- run the project using Tomcat
