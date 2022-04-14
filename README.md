# The Backend System for a Car Website
A backend system to maintain vehicle data and to provide a complete view of vehicle details including price and address.

## Vehicles API
- A REST-based Vehicles API that communicates with a location and pricing service using Java and Spring Boot.
- Used Swagger to implement API documentation.
- Tests for the controller classes.

### Functions 
Create/Retrive/Update/Delete a Vehicle.

### Features
- REST API exploring the main HTTP verbs and features
- Hateoas
- Custom API Error handling using ControllerAdvice
- Swagger API docs
- HTTP WebClient
- MVC Test
- Automatic model mapping

## Pricing Setvice
- A REST WebService that simulates a backend that would store and retrieve the price of a vehicle given a vehicle id as input. 
- A microservice registered on a Eureka server.
- Additional tests for the microservice.

## Boogle Maps
A Mock that simulates a Maps WebService where, given a latitude longitude, will return a random address.
