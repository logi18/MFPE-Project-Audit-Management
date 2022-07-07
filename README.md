# MFPE-Project-Audit-Management

This is a full-stack MFPE project built as part of Cognizant CDE internship.

Following services are part of the application:
## Frontend:
* Audit management app

## Backend:
* Authorization Microservice 
* Benchmark microservice
* checklist microservice
* Severity microservice

## Requirements
* Java 8
* Angular 12

## Setup

Launch the above mentioned 4 microservices in your IDE. Import the project as `Maven Project` and wait for the dependencies to install. If any port is unavailable in your machine you can change the port for the respective microservice in the `application.properties` file under `Backend/microservice/src/main/resources/application.properties`

After the 4 microservices are up and running launch the Audit management system  using `ng serve`
