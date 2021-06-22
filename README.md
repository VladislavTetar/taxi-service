#Taxi Service App
This is a simple application 
that representation the taxi service. 
Here we can: 
- Register or login as a **taxi 
driver**.
- View information 
about **drivers**, **cars**, 
**cars manufacturers**, which **car** 
  is registered to 
  the **driver**.
- Add new **drivers, cars** and 
**manufacturers**, register driver in different cars.
- Register **driver** in different **cars**.
- Remove information from the database. 

##Technologies used:
- Java
- JDBC
- Servlets
- MySql
- Tomcat
- JSP
- HTML
- CSS
- Apache Maven
- JSTL

##Setup
- Configure Apache Tomcat
- Install MySQL and MySQL Workbench
- Create a schema and all the necessary tables by using the script from *resources/init_db.sql* in MySQL Workbench
- In the *taxi/util/ConnectionUtil.java* class change the "user", "password", "url", "jdbc_driver" properties to 
  the ones you specified when installing MySQL 
- Start the application
