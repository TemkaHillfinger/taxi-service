# 🚖 My taxi-service 🚖
## Project description:
This is a simple application that allows you to work with a taxi service. This app follows SOLID principles and based on N-tier architecture. It supports registration, authentication, and all CRUD-based operations.


 
## <img height="30" src="https://cdn-icons-png.flaticon.com/512/2857/2857406.png" width="36"> Project structure:
- Data access tier -> handled by DAO;
- Business logic tier -> handled by Service;
- Presentation tier -> handled by Controllers and JSP pages.
 
## <img height="30" src="https://edps.europa.eu/sites/default/files/picture/technologies2.png" width="36"/> Technologies used:
- <img height="30" src="https://cdn-icons-png.flaticon.com/512/5968/5968282.png" width="36"/> Java (version 11)  
- <img height="30" src="https://images.sftcdn.net/images/t_app-logo-xl,f_auto,dpr_2/p/6ca8194c-164f-4718-930a-2bed171d0430/1359200834/apache-maven-maven-logo.png" width="36"/> Maven (version 3.11.4) 
- <img height="30" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRsGDWZvGnIggXi_v9xMGaW9qZrlPaFz_Cjjw&usqp=CAU" width="36"/> JDBC for connection to DB 
- <img height="30" src="https://camo.githubusercontent.com/f85f882cb31eeaeee657ec955313015c30378e8f56c3dc2f06933b617a276cfd/68747470733a2f2f77372e706e6777696e672e636f6d2f706e67732f3734372f3739382f706e672d7472616e73706172656e742d6d7973716c2d6c6f676f2d6d7973716c2d64617461626173652d7765622d646576656c6f706d656e742d636f6d70757465722d736f6674776172652d646f6c7068696e2d6d6172696e652d6d616d6d616c2d616e696d616c732d746578742d7468756d626e61696c2e706e67" width="36"/> MySQL as database (version 8.0.22)                                  
- <img height="30" src="https://upload.wikimedia.org/wikipedia/commons/thumb/f/fe/Apache_Tomcat_logo.svg/1280px-Apache_Tomcat_logo.svg.png" width="36"/> Apache Tomcat as web server (version 9.0.73) 
- <img height="30" src="https://cdn-icons-png.flaticon.com/512/29/29540.png" width="36"/> JSP for presentation
- <img height="30" src="https://w7.pngwing.com/pngs/131/718/png-transparent-representational-state-transfer-computer-icons-application-programming-interface-web-api-others-miscellaneous-blue-computer-network.png" width="36"/> Java Servlet API for presentation (version 4.0.1)
- <img height="30" src="https://image.winudf.com/v2/image/anN0bC5hcHBzLmdvbGQubXlhcHBsaWNhdGlvbl9zY3JlZW5fMF9qaWZycW84eA/screen-0.webp?fakeurl=1&type=.webp" width="36"/> JSTL for presentation

## <img height="30" src = "https://i.pinimg.com/564x/d5/1d/8b/d51d8b2ff28db324ed1be2766f793c43.jpg" width="36"/> DataBase structure:
![image](https://github.com/Vasyl-Piznak/my-taxi-service/assets/106866989/6dd14a33-3a69-438d-8065-a2c488312ec6)

## <img height="30" src = "https://cdn4.iconfinder.com/data/icons/scrum-process-2/64/product-capability-ability-features-requirements-512.png" width="36"/> Features:
- Registration like a driver;
- Authentication lile a driver;
- Create/update/remove a manufacturer;
- Create/update/remove a driver;
- Create/update/remove a car;
- Display list of all manufacturers;
- Display list of all drivers;
- Display list of all cars;
- Add driver to car;


## <img height="30" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQXQZfgbHHUnh8EnFosVBvL1Q9zxQAuNrlmEzCQBAGzc7VihcwrsyRzGRBuvseJz4P-0OM&amp;usqp=CAU" width="36"/>  How to launch the project on your PC:

- Fork this repo
- Create schema and all tables using the file init_db.sql
- Config ConnectionUtil.class (you need write your own data in these constants)
  ~~~java
  private static final String URL = "URL";
  private static final String USERNAME = "USERNAME";
  private static final String PASSWORD = "PASSWORD";
  private static final String JDBC_DRIVER = "JDBC_DRIVER";
  ~~~
- Install Tomcat. I am using Tomcat 9.0.73.
- Add Tomcat server to configuration
- Run project
