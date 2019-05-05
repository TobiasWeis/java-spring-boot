# Java Spring Boot Demo

## Description
This little repo contains a java spring boot demonstration to get me up to speed with some tools I did not know yet.

It has been setup using the Spring Initializr from https://start.spring.io/ and then importing it into intellij-community.
It uses Apache Maven to manage builds.

## Classes
The main classes are as follows:
* Application - wrapper to run the Spring application
* Controller - Routing and returning JSON info
* Greeting - A class to construct JSON replies

## How to run
* Import the project using IntelliJ community edition
* Server-port is currently set to 8088, can be changed in resources/application.properties
* Run the Application
* Navigate your browser to localhost:8088, optionally supply a name-argument: localhost:8088?name=Tobi
