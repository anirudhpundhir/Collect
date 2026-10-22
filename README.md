# Collect

A minimal Spring Boot starter service: one REST endpoint and an integration test. It is a skeleton, not a finished application.

## Tech stack
Java, Spring Boot 2.5.5 (Web), Maven, JUnit 5 + `TestRestTemplate`.

## What it does
`GET /` returns `Hello World, Spring Boot!`. The server listens on port `8081` (`application.properties`).

## How to run
```bash
mvn spring-boot:run          # http://localhost:8081/
mvn test
```

## Key concepts
Spring Boot auto-configuration, `@RestController`, `@SpringBootTest` with a random port.
