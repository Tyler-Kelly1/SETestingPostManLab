# Student Registration API

The system under test for the API contract and dynamic testing lab.
It is a Spring Boot REST API that manages students, courses, and course rosters.

For Part 2 Review I would recommend opening the .postman file in post man to see all single request clearly. There are also test design docs/tables in excel files at the top level of this repo.

## What you need

- JDK 17 or newer
- Maven
- Postman
- Newman (`npm install -g newman`), for running your collection from the command line

## Start the API

From the project root, run:

```bash
mvn spring-boot:run
```

The API is ready when the log says `Started StudentRegDemo`.

| What | Where |
| --- | --- |
| API base URL | `http://localhost:8080/api` |
| Swagger UI | `http://localhost:8080/swagger-ui.html` |
| OpenAPI contract (JSON) | `http://localhost:8080/v3/api-docs` |

