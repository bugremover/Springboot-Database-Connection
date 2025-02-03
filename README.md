# 🚀 Spring Boot Connection with Multi-Database

[![Spring Boot](https://img.shields.io/badge/Spring%20Boot-2.7.3-green)](https://spring.io/projects/spring-boot)  
[![Java](https://img.shields.io/badge/Java-17-blue)](https://www.java.com/)  
[![License](https://img.shields.io/badge/License-MIT-yellow)](LICENSE)

🔥 **Spring Boot Multi-Database Support** 🔥

This project demonstrates how to connect **Spring Boot** with multiple databases:
- ✅ **MySQL** (SQL database with JPA & Hibernate)
- ✅ **PostgreSQL** (SQL alternative with JPA & Hibernate)
- ✅ **MongoDB** (NoSQL database with Spring Data MongoDB)
- ✅ **Firestore** (Firebase NoSQL cloud database)

---

## 🛠️ Technologies Used

- **Spring Boot** - Framework for Java applications
- **Spring Data JPA** - ORM for SQL databases
- **Spring Data MongoDB** - MongoDB integration
- **Firebase SDK** - Firestore connectivity
- **H2 Database** - In-memory database for testing
- **Lombok** - Reduces boilerplate code

---

## ⚡ Project Structure
```
spring-boot-multi-db
│── src/main/java/com/example/demo
│   ├── controller
│   ├── model
│   ├── repository
│   ├── service
│   ├── config
│── src/main/resources
│   ├── application.yml
│── README.md
│── pom.xml
```

---

## 🚀 Getting Started

### 1️⃣ Clone the Repository
```sh
git clone https://github.com/yourusername/spring-boot-multi-db.git
cd spring-boot-multi-db
```

### 2️⃣ Setup Database Configuration
Modify the `application.yml` file to set up your database credentials.

### 3️⃣ Run the Application
```sh
mvn spring-boot:run
```

---

## 🔍 How It Works
Spring Boot provides seamless integration with multiple databases by using **Spring Data JPA** for relational databases and **Spring Data MongoDB** for NoSQL databases. Firestore integration is handled using Firebase Admin SDK.

Each repository is configured separately, allowing **flexible database switching** through `application.yml`. The architecture follows the **repository-service-controller pattern**, ensuring clean and maintainable code.

---

## 🤔 Why Use This Approach?
✅ **Flexibility**: Easily switch between different databases by changing configurations.  
✅ **Scalability**: Supports multiple databases, making it future-proof for applications.  
✅ **Best Practices**: Uses clean architecture, separating concerns effectively.  
✅ **Advanced Features**: Implements pagination, sorting, and custom queries.  

---

## 🛠️ API Endpoints
| Method | Endpoint | Description |
|--------|---------|-------------|
| GET | `/users` | Get all users |
| POST | `/users` | Add a new user |
| GET | `/users/{id}` | Get user by ID |
| PUT | `/users/{id}` | Update user |
| DELETE | `/users/{id}` | Delete user |

---

## 🎉 Features
✔️ Basic CRUD Operations for all databases  
✔️ Best practices with repository patterns  
✔️ Easy database switching via `application.yml`  
✔️ Supports relational & NoSQL databases  
✔️ Well-structured & scalable project architecture  
✔️ Implements error handling & validation  

---

## 🖼️ Screenshots
![Spring Boot Multi-DB](https://via.placeholder.com/800x400.png?text=Spring+Boot+Multi-Database+Example)

---

## 📜 License
This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

---

### 🌟 Show Your Support!
If you like this project, don't forget to ⭐ **Star the Repo!** 😃
