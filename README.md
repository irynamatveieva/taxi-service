#🚕 Taxi-Service
###Project Description:
```
A basic web-application that includes features for user authentication, 
registration, and various CRUD (Create, Read, Update, Delete) operations.
```

###🎯 Features:
- registration like a driver
- authentication like a driver
- create/update/remove a manufacturer
- create/update/remove a car
- create/update/remove a driver
- display list of all manufacturers
- display list of all drivers
- display list of all cars
- assign a driver to the car

###📚 Structure(3-layer architecture):
- DAO (Data Access Layer)
- Service (Application Logic Layer)
- Controllers (Presentation Layer)

###🦾 Technologies:
- JDK 11;
- Apache Maven;
- Apache Tomcat;
- MySQL;
- ServletAPI;
- JSP;
- JSTL;
- Git;

###📃 Installation:
- Clone this repository 
- Be sure you have installed MySQL
- Configure Tomcat. !Note: let's install Tomcat 9.0.50.
- Connect to DB: Copy and run script from the [resources/init_db.sql](resources/init_db.sql) file.
- Configure `/src/main/java/taxi/util/ConnectionUtil.java` with your database connection details(URL, username, password, and JDBC driver).
- Now you can run this application in your computer!