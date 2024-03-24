
Welcome to the Rental Car Agency application! This is a REST API service built with the Spring Boot framework, <br>
that allows you to perform CRUD operations on a car rental database. <br/>
This application is designed to demonstrate how to build a simple Spring Boot application that interacts with a MySQL
database and provides RESTful endpoints for client-side communication. <br/>

<img alt="technologies_used" src="technologies_used.png"/>

* [_Rental Car Agency_](#rental-car-agency)
    * [_Technologies Used_](#technologies-used)
    * [_Requirements_](#requirements)
    * [_Installation_](#installation)
    * [_Architecture_](#architecture)
    * [_Knowledge gained_](#knowledge-gained)
    * [_Contributing_](#contributing)
    * [_License_](#license)

## _Technologies Used_

The following technologies were used to build this application: <br/>
+ Java 17 LTS  <br/>
+ Spring Boot 3 <br/>
+ MySQL <br/>
+ JUnit <br/>
+ Maven <br/>
+ Visual Studio code <br/>
## _Requirements_

* Having **Java 17 LTS** or later installed. <br>
  You can download it
  from [bellsoft's website](https://bell-sw.com/pages/downloads/#jdk-17-lts).


* Having MySQL DataBase installed, or you can fire up an instance of MySQL using the docker-compose file provided in the
  project. <br>
  Install **MySQL** from [MySQL's website](https://dev.mysql.com/downloads/mysql/).


* Having a Client-Side application to communicate with the REST API endpoints. <br>
  Install **Apache Maven 3.9.6** from [Maven's website](https://maven.apache.org/download.cgi).

## _Installation_

1. Clone this repository to your local machine using this
   command : <br/> `git clone https://github.com/NidhalNaffati/Rental-Car-Agency.git`
2. Import the project into your IDE (such as IntelliJ IDEA or Eclipse).
3. Open the `application.yml` file located in `src/main/resources/` and update the database credentials with your own.

  ```yaml
spring:
  datasource:
    url: jdbc:mysql://localhost:3306/RentalCarDB?createDatabaseIfNotExist=true
    username: MYSQL_USERNAME
    password: MYSQL_PASSWORD
```

4. Run the application as a Spring Boot application, or using the Maven plugin `mvn spring-boot:run`.

## _Architecture_

<img alt="UML_Diagram" width="1400" height="1000" src="UML_Diagram.png"/>

## _Endpoints_

## _Knowledge Gained_

In this project, I learned how to build a REST API using Spring Boot and how to use Spring Data JPA to interact with a
MySQL database.

* Spring Boot 3 basics and how to use it to build a REST API.
* Following the RESTful API design principles.
* Using Spring Data JPA to interact with a MySQL database.
* Flyway for database migrations.
* Server and Client Side Error Handling.
* Validating user inputs or JSON object using Spring Boot Validation.
* Unit Testing using JUnit and Mockito.
* Integration Testing using Spring Boot Test.
* Dealing with Data using Spring Data JPA.
    * Fetching data using a GET api.
    * Sending data from a FORM using a POST api.
    * Editing an existing object using a PUT api
    * Deleting an existing product using a DELETE api

## _Contributing_

1. Fork this repository to your GitHub account.
2. Clone the forked repository to your local machine.
3. Create a new branch for your changes.
4. Make your changes and commit them with descriptive commit messages.
5. Push your changes to your GitHub account.
6. Create a pull request from your branch to the original repository's main branch.
7. Wait for the maintainers to review and merge your changes.

When making contributions, please keep the following in mind:

* Follow the code style and formatting guidelines used in the project.
* Write clear and concise commit messages that explain the changes you made.
* Make sure your changes do not break existing functionality.
* Write tests for new code and ensure that all existing tests pass.

## _License_

You are allowed to use, copy, modify, and distribute the code freely.
