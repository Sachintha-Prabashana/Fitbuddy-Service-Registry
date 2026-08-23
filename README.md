# ECA Gym Service Registry

## Student Information
- **Name**: R.K. Sachintha Prabashana
- **Student ID**: 241722032
- **GCP Project ID**: [Your GCP Project ID]

## Project Description
The Service Registry enables service discovery and registration for all microservices in the FitBuddy platform. It ensures seamless communication between services.

## Technology Stack
- **Programming Language**: Java
- **Framework**: Spring Boot
- **Service Discovery**: Netflix Eureka
- **Build Tool**: Maven
- **Other Tools**: Docker

## Project Structure
```
service-registry/
├── src/
│   ├── main/
│   │   ├── java/  # Application source code
│   │   ├── resources/  # Configuration files
│   └── test/  # Unit and integration tests
├── pom.xml  # Maven configuration
├── README.md  # Documentation
└── target/  # Compiled output
```

## Setup / Getting Started Instructions
1. Clone the repository.
2. Navigate to the `service-registry` directory.
3. Run `mvn clean install` to build the project.
4. Start the application using `mvn spring-boot:run`.
5. Access the Service Registry at `http://localhost:8761`.

## Dependencies
- Spring Boot Starter Web
- Spring Boot Starter Eureka Server
- Maven Surefire Plugin

## Purpose
This service acts as the backbone of the FitBuddy platform, enabling dynamic service discovery and registration for all microservices.
