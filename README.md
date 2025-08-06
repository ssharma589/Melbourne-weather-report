# Melbourne Weather Report API

This is a Spring Boot application created in STS that reports weather data for Melbourne using:
- WeatherStack API (Primary)
- OpenWeatherMap API (Failover)

##Features

- RESTful GET endpoint: `/v1/weather?city=melbourne`
- Fallback mechanism between APIs
- 3-second caching with stale fallback
- Unit tests using JUnit & Mockito

##Requirements

- Java 17
- Maven

##How to Run Locally

1. Unzip the project
2. Open in Spring Tool Suite (STS)
3. Run the application from the main class or just right click on project and run as Spring Boot Application

##Open browser Hit this URL 

-http://localhost:8000/v1/weather?city=melbourne
