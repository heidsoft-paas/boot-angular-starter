# Boot Angular Starter #

This is a starter app which uses Spring Boot for the server component and AngularJS for the client component.

## Project ##

The project is built using a multi-module Maven build.  It includes a single module "first-module" which is setup as a
Spring Boot web application using Jetty as the embedded container.  It also depends on Spring Boot's Actuator starter POM.

## Server ##

Just a minimal Application.java which which uses Spring Boot's @EnableAutoConfiguration symantics.

## Client ##

An AngularJS front end application built using Yeomand and the AngularJS generator (generator-angular).  You will need
NodeJS and npm install, as well as Bower and Grunt.
