#  AI-Based Task Management System – Backend (Spring Boot)

This is the **backend module** of the **AI-Based Task Management System**, built using **Spring Boot**.  
It provides RESTful APIs for user management, task creation, task assignment, project tracking, and integrates with an AI module for smart task suggestions.

---

## Tech Stack

- **Java 17+**
- **Spring Boot**
- **Spring Data JPA**
- **MySQL**
- **Spring Security (if used)**
- **Maven**
- **REST APIs**

---

## Folder Structure

```
src/
├── main/
│   ├── java/
│   │   └── com/yourorg/taskmanager/
│   │       ├── controller/
│   │       ├── model/
│   │       ├── repository/
│   │       ├── service/
│   │       └── TaskManagerApplication.java
│   └── resources/
│       ├── application.properties
│       └── data.sql (optional)
```

---

## How to Run (Locally)

1. Clone the repository:
   ```bash
   git clone https://github.com/your-org-name/your-backend-repo.git
   cd your-backend-repo
   ```

2. Update the `application.properties` file:
   ```properties
   spring.datasource.url=jdbc:mysql://localhost:3306/taskdb
   spring.datasource.username=root
   spring.datasource.password=yourpassword
   spring.jpa.hibernate.ddl-auto=update
   ```

3. Run the project:
   - Using terminal:
     ```bash
     ./mvnw spring-boot:run
     ```
   - Or open in **VS Code / IntelliJ.eclipse/STS** and run `TaskManagerApplication.java`

---



> Detailed API documentation coming soon (or add Swagger).

---

##  AI Integration (Overview)

- This backend interacts with a **Flask-based AI module** to get:
  - Task priority suggestions
  - Smart task assignment
- Communication is done via REST API calls between Spring Boot and the AI service.

---

##  Team Collaboration Notes

- Do **not** commit directly to the `main` branch.
- Always create a feature branch and make a **pull request**.
- Backend and AI logic are separated into different modules for modularity.

---

##  Author & Maintainer

**Team Lead**: [Pooja Sharma]
Feel free to raise issues or pull requests for improvements!# backend
