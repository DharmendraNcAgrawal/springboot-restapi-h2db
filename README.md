# springboot-restapi-h2db
Springboot Rest H2 Spring Data JPA

referances :
https://www.javacodegeeks.com/2018/08/restful-api-spring-rest-data-jpa-h2.html
https://www.javaguides.net/2019/08/spring-boot-crud-rest-api-spring-data-jpa-h2-database-example.html

use JDBC URL -> jdbc:h2:mem:testdb

Build and run the app using maven
--------------------------------
mvn package
java -jar target/easy-notes-1.0.0.jar

Alternatively, you can run the app without packaging it using -
mvn spring-boot:run
The app will start running at http://localhost:8080.
