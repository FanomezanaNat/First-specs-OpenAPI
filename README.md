# Onboarding API Documentation

This API provides endpoints to manage students and teachers.

[Swagger UI Documentation](https://petstore.swagger.io/?url=https://raw.githubusercontent.com/FanomezanaNat/First-specs-OpenAPI/main/openapi.yaml)

## Base URL

The API base URL is: `https://STD22005.com`

## Endpoints

### Students

- **POST /students**: Add a new student.
- **GET /students**: Retrieve a list of students.
- **PUT /students/{id}**: Update a student by ID.
- **DELETE /students/{id}**: Delete a student by ID.

### Teachers

- **POST /teachers**: Add a new teacher.
- **GET /teachers**: Retrieve a list of teachers.
ID.

## Schemas

- **Student**: ID (integer), Name (string), Birth Date (string).
- **Teacher**: First Name (string), Last Name (string), Courses (array of strings).
