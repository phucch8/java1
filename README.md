# Spring Boot Hello World

This is a simple Spring Boot application that exposes a REST endpoint at `/` returning `Hello, World!`.

## How to Run

1. Make sure you have Java and Maven installed.
2. In the root directory, run:
   ```powershell
   mvn spring-boot:run
   ```
3. Open your browser and go to http://localhost:8080/

You should see `Hello, World!` displayed.

## Project Structure
- `src/main/java/com/example/springboothello/HelloWorldApplication.java`: Main Spring Boot application.
- `src/main/java/com/example/springboothello/HelloController.java`: REST controller.

---

This project was generated as a minimal example for Spring Boot with Maven.
