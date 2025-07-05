📦 Spring Boot JWT Authentication API
A Spring Boot 3.2.5 application that provides user authentication using JWT (JSON Web Tokens), Spring Security, Spring Data JPA, and MySQL.

🚀 Features
User registration (/auth/v1/signup)

User login with JWT generation (/auth/v1/login)

Token refresh (/auth/v1/refreshToken)

Role-based access control

JWT-based stateless authentication

Secure password handling with BCrypt

Hibernate + MySQL integration

Token persistence in database

🛠️ Tech Stack
Java 17+

Spring Boot 3.2.5

Spring Security

Spring Data JPA (Hibernate)

MySQL

JWT (jjwt)

Maven

HikariCP for DB connection pooling

📬 API Endpoints
Method	Endpoint	Description
POST	/auth/v1/signup	Register new user
POST	/auth/v1/login	Login and get token
POST	/auth/v1/refreshToken	Get new access token

🔐 Security
JWT tokens are used for authentication and stored in a tokens table.

Tokens have an expiry and can be refreshed using the refresh endpoint.

Passwords are stored securely using BCrypt.

