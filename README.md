# Taxi-Service
![This is an image](https://ouch-cdn2.icons8.com/nw-wW1hgtDwp8Eam_sOUMcp8z_cA1EL45k-iZuARpAg/rs:fit:784:784/czM6Ly9pY29uczgu/b3VjaC1wcm9kLmFz/c2V0cy9zdmcvNzU0/LzQwMjljZGI3LTdh/YmEtNGI2OS1hYzIx/LTNlNDg4ZjMwY2Y4/NC5zdmc.png)
## General info
*This application simulates the operation of a taxi service. Created to demonstrate knowledge of Java-Core, OOP,
SOLID principles, working with databases and web technologies.*
## The current functionality of the program

- Login
- Display All Drivers
- Display All Cars
- Display All Manufacturers
- Create new Driver
- Create new Car
- Create new Manufacturer
- Add Driver to Car
- Get Current Cars For Driver

## Technologies
*The following technologies were used in the project:*
```
Apache Tomcat (v9.0.55)
MySQL (v8.0.25)
JDBC
Servlet
JSP
JSTL
HTML, CSS
Maven
Maven Checkstyle Plugin
```
## Setup
*Step-by-step instructions for starting and testing a project*
```
install [Tomcat 9.0.50](https://archive.apache.org/dist/tomcat/tomcat-9/v9.0.50/bin/) and [MySQL](https://www.mysql.com/downloads/) 
* fork and clone [this](https://github.com/Eugene-exe/taxi-service) project
* create your database using init_db.sql file
* add your DB Properties to ConnectionUtil class in util package
* deploy this project using Tomcat local server 
```
## Suggestions for improvement
*Add an admin account, register only ordinary users with less functionality, which will be a more real simulation 
of a taxi service*