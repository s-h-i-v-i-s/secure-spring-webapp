# secure-spring-webapp

This repository contains a simple Spring MVC web application demonstrating how to secure web resources using Spring Security.

## What You Will Build

You will build a Spring MVC application that secures pages with a login form backed by a fixed list of users.

## Prerequisites

- About 15 minutes
- A favorite text editor or IDE
- Java 17 or later
- Gradle 7.5+ or Maven 3.5+

## Getting Started

You can start from scratch or skip the basic setup steps. 

To start from scratch, move on to [Starting with Spring Initializr](#starting-with-spring-initializr).

To skip the basics, download or clone this repository and jump ahead to [Create an Unsecured Web Application](#create-an-unsecured-web-application).

## Starting with Spring Initializr

You can use [Spring Initializr](https://start.spring.io) to initialize the project. This guide assumes you choose Java, Spring Web, and Thymeleaf dependencies.

Alternatively, you can fork this project or clone it from GitHub and import it into your IDE.

## Create an Unsecured Web Application

Before applying security, you need to create a simple web application. Follow the instructions in the guide to set up views, controllers, and configure Spring MVC.

## Set up Spring Security

Once you have an unsecured web application, you can add security to it. Follow the instructions in the guide to configure Spring Security to protect resources, handle authentication, and create a login page.

## Run the Application

You can run the application using Gradle or Maven. Build an executable JAR file and run it using `java -jar`, then navigate to http://localhost:8080 in your browser.

## Repository Structure

- `src/main/java`: Contains Java source code.
- `src/main/resources`: Contains application resources.
- `src/test`: Contains test code.
- `build.gradle` or `pom.xml`: Project build files.

## Contributing

Feel free to contribute to this project by opening issues or pull requests.

## License

This project is licensed under the [MIT License](LICENSE).
