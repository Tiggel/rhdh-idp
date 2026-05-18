# ${{ values.name }}

${{ values.description }}

## Prerequisites

- Java 17+
- Maven 3.9+

## Getting started

```bash
./mvnw spring-boot:run
```

The service starts on port `8080`.

## Health check

```
GET /actuator/health
```

## Build

```bash
./mvnw clean package
```
