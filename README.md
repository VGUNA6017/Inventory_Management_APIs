# Inventory Management API

A Spring Boot-based RESTful API for managing inventory, providing endpoints for creating, reading, and managing products.

## Features

- Product creation and retrieval
- Error handling with custom exceptions
- API documentation with Swagger
- Unit testing with JUnit and Mockito
- H2 in-memory database for easy setup and testing

## Endpoints

- `POST /api/inventory/addproducts`: Creates a new product
- `GET /api/inventory/getProduct/{id}`: Get Product details using ID
- `GET /api/inventory/{id}/low-stocks`: Get all low stocks using ID
- `PUT /api/inventory/{id}/increase-stock`:Update a list of all increase-stock products
- `PUT /api/inventory/{id}/decrease-stock`: Update a list of all decrease-stock products
- `PUT /api/inventory/update/{id}`: Update all Product details
- `DELETE /api/inventory/delete/{id}`: Delete the Product details Using ID


## Error Handling

- Custom exceptions for Insufficient Stock and Product Not Found
- Global exception handling with `@RestControllerAdvice`

## Technologies Used

- ### Spring Boot
- ### H2 in-memory database
- ### Swagger for API documentation
- ### JUnit and Mockito for unit testing

## Getting Started

1. Clone the repository
2. Build the project using Maven
3. Run the application using `mvn spring-boot:run`
4. Access the API documentation at `http://localhost:8000/swagger-ui.html`

## API Documentation

API documentation is available at `http://localhost:8000/swagger-ui.html`. You can use the Swagger UI to try out API calls and see the responses.

## Testing

Unit tests are written using JUnit and Mockito. You can run the tests using `mvn test`.

# Developed By GUNA V
