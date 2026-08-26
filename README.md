# ECA Gym Service Registry

## Student Information
- **Name**: R.K. Sachintha Prabashana
- **Student ID**: 241722032
- **GCP Project ID**: `fitbuddy-505618`

## Project Description
The Service Registry enables service discovery and registration for all microservices in the FitBuddy platform. It ensures seamless communication between services.

## Technology Stack
- **Programming Language**: Java 25
- **Framework**: Spring Boot 4.0.1
- **Service Discovery**: Spring Cloud Netflix Eureka Server
- **Build Tool**: Maven

## Project Structure
```
service-registry/
├── src/
│   ├── main/
│   │   ├── java/  # Application source code
│   │   ├── resources/  # Configuration files
│   └── test/  # Unit and integration tests
├── pom.xml  # Maven configuration
└── README.md  # Documentation
```

## Setup / Getting Started Instructions
1. Clone the repository.
2. Navigate to the `service-registry` directory.
3. Run `./mvnw clean install` to build the project.
4. Start the application using `./mvnw spring-boot:run`.
5. Access the Service Registry at `http://localhost:9000`.

## Dependencies
- Spring Boot Starter Web
- Spring Boot Starter Eureka Server
- Maven Surefire Plugin

## Purpose
This service acts as the backbone of the FitBuddy platform, enabling dynamic service discovery and registration for all microservices.
