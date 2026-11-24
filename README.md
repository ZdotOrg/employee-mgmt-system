# Employee Management System

A Java application for managing employee records and generating pay reports, backed by MySQL. Currently a console app, being converted into a Spring Boot REST API.

## Tech Stack

- Java 17+
- MySQL
- JDBC (current) → Spring Boot, Spring Data JPA (in progress)
- Maven
- Docker Compose (planned)

## Features

**Implemented**
- Add employees
- Search by SSN, name, or employee ID
- Bulk salary increase by salary range and percentage
- Monthly pay reports by division and by job title

**Planned**
- Full CRUD REST API
- Input validation and global exception handling
- Pagination and filtering
- Unit and integration tests (JUnit, MockMvc)
- Swagger/OpenAPI documentation
- SSN masking/encryption
- Monthly pay statements
- Authentication (Spring Security + JWT)

## Getting Started

### Prerequisites
- JDK 17+
- MySQL 8+ (or Docker)
- Maven

### Setup
1. Clone the repo:
   ```bash
   git clone https://github.com/ZdotOrg/employee-mgmt-system.git
   cd employee-mgmt-system
   ```
2. Create the database and table:
   ```bash
   mysql -u root -p < schema.sql
   ```
3. Configure your database credentials (environment variables or `application-local.properties`).
4. Run the application.

> Setup steps will be updated as the Spring Boot conversion is completed.

## Roadmap

- [x] Console-based CRUD and reports
- [ ] `schema.sql` with sample data
- [ ] Docker Compose for MySQL
- [ ] Migrate to Spring Boot REST API
- [ ] Validation and error handling
- [ ] Tests
- [ ] API documentation
- [ ] Security improvements

## License

TBD