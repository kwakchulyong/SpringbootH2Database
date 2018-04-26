# SpringbootH2Database
made a board by Spring boot + H2(embedded database)
<br/>
<h2>Development environment</h2>
Spring Tool Suite 3.9.4<br/>
JAVA8<br/>
TOMCAT8<br/>
Maven<br/>
H2<br/>
JPA<br/>
JDBC<br/>
Hibernate<br/>
Spring Boot 2.0.1<br/>
bootstrap 4.1.0<br/>
Jquery 3.3.1

<h2>File List</h2>
pom.xml<br/>
src/main/resources/application/properties<br/>
src/main/resources/application/data.sql<br/>
src/main/resources/application/schema.sql<br/>
src/main/java/com/test/SpringBoot2JdbcWithH2Application.java<br/>
src/main/java/com/test/controller/MemberController.java<br/>
src/main/java/com/test/member/Member.java<br/>
src/main/java/com/test/member/MemberJdbcRepository.java

<h2>How to run</h2>
1. Open the Spring Tool Suite eclipse<br/>
2. Download source code<br/>
3. Import -> Existing Maven Projects->Choose Root Directory<br/>
4. Run as -> Spring boot App<br/>
5. Open the Web browser : http://localhost:8080/


Index page
![title](/screenshoot/1.png)
Validation Check
![title](/screenshoot/2.png)

• The username field accepts alpha-numeric values only
• The username length is no less than 5 characters
• The username is not already registered
• The password has a minimum length of 8 characters and contains at least 1 number, 1
uppercase, and 1 lowercase character
• The user gets feedback when the username or the password doesn't meet the criteria
• Upon submission of a valid username and password, they are persisted to a database
• The user gets feedback that he/she has been registered

List page
![title](/screenshoot/3.png)
H2 Database Console-1
![title](/screenshoot/4.png)
H2 Database Console-2
![title](/screenshoot/5.png)
