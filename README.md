# Prevail Backend

Backend service for the Prevail task management platform.

## Overview

Prevail is a task and planning system centered around:
- seeds (ideas/inspirations)
- tasks
- commitments/plans
- progress tracking

This repository contains the Spring Boot backend API.

## Tech Stack

- Java 21
- Spring Boot
- Gradle
- PostgreSQL
- JPA / Hibernate

## Goals

This project is intended to:
- practice modern backend architecture
- build production-style REST APIs
- explore authentication and authorization
- model complex task workflows
- gain experience with cloud-ready backend development

## Development Status

Early development.

## Running Locally

### Prerequisites

- Java 21
- Gradle 8+

### Run the application

```bash
./gradlew bootRun
```

On Windows:

```powershell
gradlew.bat bootRun
```

### Run tests

```bash
./gradlew test
```

## Project Structure

```text
src/
 ├── main/
 │    ├── java/
 │    └── resources/
 └── test/
```

## Future Plans

- User authentication
- Task dependency modeling
- Daily planning workflow
- Notifications/reminders
- Frontend Flutter integration
- Cloud deployment

## License

MIT
