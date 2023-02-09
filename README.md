# 🚖 Taxi service 🚖
![taxi22.jpg](src%2Fmain%2Fimages%2Ftaxi22.jpg)
The goal of this project is to create a taxi service with authentication system.
During the first launch you will be redirected to a login page where you have two opportunities:
 - register a new driver
 - login as a previously registered driver.

To use all features you need to create new driver and authenticate
Driver can:
- add himself to different cars
- create new manufacturer of car
- create new car 
- create new driver<br/>
All functionality you can find by starting the app
 ---
## Implementation details
Project based on 3-layer architecture:
- Presentation layer (controllers)
- Application layer (services)
- Data access layer (DAO)
---
## Technologies
- Tomcat
- Servlet
- JDBC
- MySQL
- JSP 
- CSS<br/>
---
 ## Setup
1. Clone the repo: [link](https://github.com/leonid-topal/taxi-service.git)
2. Install MySQL
3. Configure Apache Tomcat
4. Copy and run SQL script src/main/resources/init_db.sql to creating a schema and tables for the project
5. Configure src/main/java/taxi/util/ConnectionUtil.java with your URL, USERNAME, PASSWORD, JDBC_DRIVER
6. Start Tomcat server <br/>
---
   Done. Now just try to use it.
![taxi9.png](src%2Fmain%2Fimages%2Ftaxi9.png)
