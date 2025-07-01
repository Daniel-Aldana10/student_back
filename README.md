# Student Registration API

This is a simple backend project built with **Spring Boot**, using **MongoDB** for data storage via **Spring Data MongoDB**, and following a **JPA-like repository structure** to manage entities.

---

## ech Stack

- Java 17+
- Spring Boot 3.x
- Spring Web
- Spring Data MongoDB
- MongoDB Atlas (NoSQL database)
- Maven

---

##Project Purpose

The main goal of this backend is to:

- Create and store student information (name, email, birth date, program).
- Connect to MongoDB Atlas (cloud).
- Expose RESTful endpoints for:
    - Creating a new student
    - Retrieving all registered students
- Be used in combination with a React + Vite frontend.

---

## Project Structure
```
student_back/
├── src/
│ ├── main/
│ │ ├── java/com/example/student/
│ │ │ ├── Student.java
│ │ │ ├── StudentRepository.java
│ │ │ └── StudentApplication.java
| | | └── StudentController.java
│ └── resources/
│ └── application.properties
```

### REST API Endpoints

|Method	| Endpoint	| Description |
|-------|-----------|-------------|
|POST |  	/api/students	|Create a new student|
|GET  |	/api/students	|Get all students|


# How to Run
1. Clone the repository:
```bash
git clone https://github.com/Daniel-Aldana10/student_back.git
cd student_back
```

2. Build the project:

```bash
mvn clean package
```

3. Run the application:

```bash
mvn spring-boot:run
```

By default, it will be available at:  
`http://localhost:8080/`

---

## Author

Daniel Aldana — [GitHub](https://github.com/Daniel-Aldana10)