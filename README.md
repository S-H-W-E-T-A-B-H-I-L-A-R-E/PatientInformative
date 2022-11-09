# PatientInformative

Patient Informative is a project module used for saving the patient data in database from any xls format and fetch the details of patient.

For building and running the application you need:

- [JDK 1.8](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)
- [Maven 3](https://maven.apache.org)

## Project set up
Open the project in any IDE(STS, intellij etc) : https://www.jetbrains.com/idea/download/#section=windows

Import project as maven project

Let the dependencies install

Install JAVA JDK 11.0.16 version : https://www.oracle.com/in/java/technologies/javase/jdk11-archive-downloads.html

Add the SDK of java 11 or higher version to run the application
 
## Running the application locally

There are several ways to run a Spring Boot application on your local machine. One way is to execute the `main` method in the `PatientApplication` class from your IDE.

## Set up the database 
Database for this project is Postgresql

Install the postgresql in your local machine : https://www.postgresql.org/download/windows/

Install a software to view the database ex. DBeaver, pgAdmin, DBVisualizer etc.

https://dbeaver.io/download/

Add the dump file into the database 

## API Call
Install Postman to run the API's : https://www.postman.com/downloads/

Add the urls of the API in the Postman console

## local URLs for API's to run locally
http://localhost:8080/admin/getDataByGender?gender=female

http://localhost:8080/admin/getAllData

http://localhost:8080/admin/getDataByCovidRisk?covidRisk=High

http://localhost:8080/save?file

