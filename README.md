# Spring Boot Form Demo

A lightweight Spring Boot application that demonstrates how to capture and display form input using Thymeleaf.

## Technologies Used
* **Java 17**
* **Spring Boot 3.2.x** (Web, Thymeleaf)
* **Maven**

## Features
* Simple HTML form to capture user details (Name, Email).
* Styled with basic CSS for a clean look.
* Submission handling via Spring MVC and Thymeleaf template rendering.

## How to Run

1. **Clone the repository** (if applicable) or navigate to the project root directory.
2. **Build and run** the application using Maven:
   ```bash
   ./mvnw spring-boot:run
   ```
   *Alternatively, you can run the `DemoApplication` class directly from your IDE.*
3. **Open in browser**:
   Navigate to [http://localhost:8080](http://localhost:8080) to view the form.

## Project Structure
* `src/main/java/com/example/demo/` - Contains the Java source code (Application, Controller, Model).
* `src/main/resources/templates/` - Contains the Thymeleaf HTML templates (`form.html`, `result.html`).
