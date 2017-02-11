# Authentication with Spring Boot, AngularJS and Keycloak

- Make sure to start Keycloak before using the application

## Run with embedded Server

To run the project with embedded Tomcat by maven:

    mvn spring-boot:run
  
To run the project with embedded Jetty by maven:

    mvn spring-boot:run -Pjetty

To run the project with embedded Undertow by maven:

    mvn spring-boot:run -Pundertow

Then navigate to [http://localhost:8000](http://localhost:8000) to see the application in action.
