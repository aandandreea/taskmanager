# Task Manager API

A simple RESTful API for managing tasks, built with **Spring Boot**, **Spring Data JPA**, and **Jakarta Bean Validation**. Supports full CRUD operations, with input validation and centralized error handling.

## Features

- Create, read, update, and delete tasks
- Task status (`TODO`, `IN_PROGRESS`, `DONE`) and priority (`LOW`, `MEDIUM`, `HIGH`)
- Input validation (title required, status/priority required)
- Centralized exception handling with clean JSON error responses

## Tech Stack

- Java, Spring Boot
- Spring Web (REST)
- Spring Data JPA
- Jakarta Bean Validation

## Future Improvements

- Return proper HTTP status codes (`201 Created`, `204 No Content`)
- Handle malformed JSON / invalid enum values gracefully
- Add pagination and filtering
- Add unit and integration tests
- Add authentication
