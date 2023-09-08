🚖 My taxi-service 🚖

Project description:

This is a simple application that allows you to work with a taxi service. This app follows SOLID principles and based on N-tier architecture. It supports registration, authentication, and all CRUD-based operations.



Project structure:

Data access tier -> handled by DAO;
Business logic tier -> handled by Service;
Presentation tier -> handled by Controllers and JSP pages.
Technologies used:

Java (version 11)
Maven (version 3.11.4)
JDBC for connection to DB
MySQL as database (version 8.0.22)
Apache Tomcat as web server (version 9.0.73)
JSP for presentation
Java Servlet API for presentation (version 4.0.1)
JSTL for presentation
DataBase structure:

image

Features:

Registration like a driver;
Authentication lile a driver;
Create/update/remove a manufacturer;
Create/update/remove a driver;
Create/update/remove a car;
Display list of all manufacturers;
Display list of all drivers;
Display list of all cars;
Add driver to car;
How to launch the project on your PC:

Fork this repo
Create schema and all tables using the file init_db.sql
Config ConnectionUtil.class (you need write your own data in these constants)
private static final String URL = "URL";
private static final String USERNAME = "USERNAME";
private static final String PASSWORD = "PASSWORD";
private static final String JDBC_DRIVER = "JDBC_DRIVER";
Install Tomcat. I am using Tomcat 9.0.73.
Add Tomcat server to configuration
Run project