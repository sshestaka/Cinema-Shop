# Cinema Booking System

**Welcome to the "Cinema Booking System," a Java-based application designed to streamline the cinema experience for both users and administrators. Leveraging the power of Hibernate and MySQL, this application offers a robust and efficient solution for managing cinema halls, movies, sessions, orders, and user interactions.**

## Project structure:

**1.	DAO Level:**<br>
•	Cinema Hall Dao<br>
•	Movie Dao<br>
•	Movie Session Dao<br>
•	Order Dao<br>
•	Shopping Cart Dao<br>
•	Ticket Dao<br>
•	User Dao<br><br>
**2.	Exception Level:**<br>
•	Authentication Exception<br>
•	Data Processing Exception<br>
•	Registration Exception<br><br>
**3.	Lib Level:**<br>
•	@Dao<br>
•	@Inject<br>
•	@Service<br>
•	Injector class<br><br>
**4.	Model Level:**<br>
•	Cinema Hall<br>
•	Movie<br>
•	Movie Session<br>
•	Order<br>
•	Shopping Cart<br>
•	Ticket<br>
•	User<br><br>
**5.	Security Level:**<br>
•	Authentication Service and its Implementation<br><br>
**6.	Service Level:**<br>
•	Cinema Hall Service<br>
•	Movie Service<br>
•	Movie Session Service<br>
•	Order Service<br>
•	Shopping Cart Service<br>
•	User Service<br><br>
**7.	Util Level:**<br>
•	Hash Util class for password hashing with Salt<br>
•	Hibernate Util class for creating the Session Factory<br><br>
**8.	Main Method:**<br>
•	Demonstrates app logic with necessary creations and checks.<br><br>
**9.	Hibernate.cfg.xml:**<br>
•	Holds all Hibernate configurations for connecting to MySQL DB and creating tables.<br><br>

## Technologies and Tools:<br>
•	Java 17<br>
•	Hibernate 6.2.7.Final<br>
•	MySQL Connector Java 8.0.33<br>
•	Maven Checkstyle Plugin 3.3.0<br><br>

## Features:<br>
**1.	Data Access Objects (DAO):<br>**
•	Interfaces and Implementations for various entities.<br><br>
**2.	Custom Exceptions:<br>**
•	Handles authentication, data processing, and registration exceptions.<br><br>
**3.	Annotations and Injector:<br>**
•	Utilizes @Dao, @Inject, @Service annotations, and an Injector class.<br><br>
**4.	Models:<br>**
•	Defines entities such as Cinema Hall, Movie, Order, etc.<br><br>
**5.	Security:<br>**
•	Implements Authentication Service for secure user interactions.<br><br>
**6.	Service Layer:<br>**
•	Interfaces and Implementations for various services.<br><br>
**7.	Utilities:<br>**
•	Provides utility classes for password hashing and Hibernate sessions.<br><br>
**8.	Main Method:<br>**
•	Demonstrates the application's core logic.<br><br>
**9.	Hibernate Configuration:<br>**
•	Configures Hibernate to connect to MySQL DB and create tables.<br><br>

## How to Use:<br>
1.	Clone the repository.<br>
2.	Configure the MySQL database.<br>
3.	Run the main method to demonstrate the application's logic.<br><br>

**Explore the "Cinema Booking System" for a seamless and enjoyable cinema experience!**

### Model structure 
![pic](Hibernate_Cinema_Uml.png)
