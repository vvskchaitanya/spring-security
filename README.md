# spring-security
This repository contains practical examples and tutorials on using Spring Security to secure Java applications.

## Prerequisites
- Java Development Kit (JDK) installed
- Apache Maven installed

## Getting Started
1. [Spring Security Starter](##spring-security-starter)
2. [Spring Security REST API](##spring-security-rest-api)
3. [Spring Security OAuth2](##spring-security-oauth2)
4. [Spring Security JWT](##spring-security-jwt)


## Spring Security Starter
A simple Spring Boot web application with spring-security-starter dependency.

- Open https://start.spring.io/
- Choose Build as Maven, Language as Java, Enter Project details, Choose jar and Generate Spring Boot Project
- Choose Dependencies Web, Security
- Unzip the downloaded project to specific location and import the project into your IDE (Eclipse / IntelliJ / VSCode)
- Navigate into project directory
```sh
cd spring-security-starter
```
- Clean the project
```sh
mvn clean
```
- Intsall the project
```sh
mvn install
```
- Run the application
```sh
mvn spring-boot:run
```
- Open the application in browser http://localhost:8080

## Spring Security REST API
To build REST API using spring web module and adding security roles to access different REST API endpoints 

## Spring Security OAuth2
Understand How to create Authorization Server and Resource Server using spring security oauth2 module and secure endpoints

## Spring Security JWT
Understand importacnce of JWT and login endpoint to grab the user credentials and return JWT to client
Provide roles and claims in JWT and authorize the requests before providing access to secure endpoints





