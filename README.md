# taxi-service-jdbc

This is a java demo project mocking the work 
of taxi and driver control system.

Here you can create your driver account 
- on registration page and connect it to the cars,
- use login/logout pages,
- create, update and remove cars, manufacturers and drivers,
- display lists of cars, drivers or manufacturers.

### Structure of the project is based on N-tier architecture:
- DAO layer - database
- Service layer - business logic
- Controllers - accept requests and send responses
- Views - presentation layer

![](C:\dev\MA\taxi-service-jdbc\taxi_models_diagram_mini.jpg)

### Technologies used in the project:
- Java 11
- JDBC
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
