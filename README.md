# 🧠 ShortBit Backend

This is the **Spring Boot backend** for the ShortBit URL Shortener application. It handles authentication, authorization, URL shortening logic, user management, and link analytics.

---

## 🌐 Deployed API

📦 Base URL: `https://shortbit-sb.onrender.com/api`

---

## 🛠️ Tech Stack

- Java 17
- Spring Boot
- Spring Security + JWT
- MySQL
- Hibernate (JPA)
- Maven
- Render (Deployment)

---

## 🔐 Key Features

- JWT-based authentication
- Secure login/register endpoints
- URL shortening and redirection
- Link management per user
- CORS support for frontend integration

---

## 📁 Project Structure
```bash
backend/
├── src/
│ ├── main/
│ │ ├── java/com/url/shortener/
│ │ │ ├── controllers/
│ │ │ ├── dtos/
│ │ │ ├── model/
│ │ │ ├── repository/
│ │ │ ├── security/
│ │ │ ├── service/
│ │ └── resources/
│ │ └── application.properties
├── pom.xml
```

---

## 🔧 Installation & Run

```bash
cd backend
./mvnw spring-boot:run
```
---

## 🔌 API Endpoints

| Method | Endpoint                   | Description         |
| ------ | -------------------------- | ------------------- |
| POST   | `api/auth/public/register` | Register new user   |
| POST   | `api/auth/public/login`    | Login and get token |

---
## 🧪 Environment Setup

```bash
spring.datasource.url=jdbc:mysql://localhost:3306/shortbit
spring.datasource.username=root
spring.datasource.password=your_password
spring.jpa.hibernate.ddl-auto=update
jwt.secret=your_jwt_secret_key
```

## 🙋‍♂️ Author
```bash
Ashish Kumar
GitHub: @ashishkumar-17
```
