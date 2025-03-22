# User Management System 🚀

## Overview
This is a **Spring Boot 2.7.18 & Java 8** application for managing users with CRUD operations, form validation, and API integration.

## Features ✨
- User Registration & Authentication (Spring Security)
- Profile Management (CRUD)
- Form Validation (Server-Side)
- REST API for User Management
- Secure Password Storage

## Technologies Used 🛠️
- **Spring Boot 2.7.18**
- **Java 8**
- **Spring Security**
- **Spring Data JPA**
- **MySQL**
- **Maven**

## Installation 📥
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/your-repository.git
   cd your-repository
   ```
2. Configure **MySQL Database** in `src/main/resources/application.properties`:
   ```properties
   spring.datasource.url=jdbc:mysql://localhost:3306/user_db
   spring.datasource.username=root
   spring.datasource.password=yourpassword
   ```
3. Build & run the project using Maven:
   ```sh
   mvn spring-boot:run
   ```
4. Access the APIs via **Postman** or **cURL**.

## API Endpoints 🛠️
| Method | Endpoint           | Description |
|--------|--------------------|-------------|
| POST   | `/users/register`  | Register a new user |
| POST   | `/users/login`     | Login user |
| GET    | `/users/{id}`      | Get user details |
| PUT    | `/users/{id}`      | Update user profile |

## Contributing 🤝
Feel free to fork and improve the project. Pull requests are welcome!

git add README.md
git commit -m "Added README file"
git push origin main
```

