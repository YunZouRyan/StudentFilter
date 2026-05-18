# StudentFilter

A Java-based web application for managing and filtering student records. Users can view all students, apply multiple filters simultaneously (enrollment date, GPA threshold, GPA range, program, name search), and see the filtered results in a table view.

## Features
- View all students sorted by enrollment date
- Filter students by multiple criteria, applied in combination:
  - Enrolled after a specific date
  - GPA above a threshold
  - GPA within a specified range
  - Program of study
  - Name contains a keyword
- Pre-seeded database with sample student data on startup

## Requirements
- Java 17
- Maven

## Technologies
- **Language:** Java 17
- **Framework:** Spring Boot 3.4.2
- **Persistence:** Spring Data JPA, Hibernate, H2 (in-memory), MySQL (optional)
- **Frontend:** Thymeleaf, Bootstrap 4.5.2
- **Web:** Spring MVC
- **Build Tool:** Maven
- **Dev Tools:** Spring Boot DevTools (hot reload)
- **Other:** Lombok (`@Data`, `@AllArgsConstructor`, `@NoArgsConstructor`, `@RequiredArgsConstructor`)

## Getting Started
Clone the repository and run the application:

```bash
mvn spring-boot:run
```

Once started, navigate to `http://localhost:8080/` in your browser.

The H2 console is available at `http://localhost:8080/h2-console/` (JDBC URL: `jdbc:h2:mem:testdb`).
