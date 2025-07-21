# 🛠️ Simple Spring Boot CRUD Application

This is a basic **CRUD (Create, Read, Update, Delete)** application built using **Spring Boot**, **Spring Data JPA**, and **H2 in-memory database**. It features a RESTful API to manage a simple entity, demonstrating how to set up and interact with a Spring Boot backend.

> 🔨 This project is based on the tutorial: _"CRUD App in 30 mins | Simplest Explanation | Spring Boot | REST | JPA | H2"_  
> 🧠 I used the video as a learning reference and then customized the implementation to solidify my understanding and improve my backend development skills.

---

## 🚀 Technologies Used

- **Spring Boot**
- **Spring Web (REST API)**
- **Spring Data JPA**
- **H2 Database**
- **Maven**

---

## 📂 Project Structure

```
src/
├── main/
│   ├── java/com/example/crud/
│   │   ├── controller/
│   │   ├── model/
│   │   ├── repository/
│   │   └── CrudApplication.java
│   └── resources/
│       ├── application.properties
│       └── data.sql (optional)
```

---

## ⚙️ How to Run

1. **Clone the repository:**

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

2. **Build and run the project:**

```bash
./mvnw spring-boot:run
```

3. **Access the API:**

You can test the API using Postman or any REST client:

| Method | Endpoint           | Description          |
|--------|--------------------|----------------------|
| GET    | `/getAllBooks`       | List all items       |
| POST   | `/addBook`       | Create a new item    |
| GET    | `/getBookById/{id}`  | Get item by ID       |
| PUT    | `/updateBookById/{id}`  | Update item by ID    |
| DELETE | `/deleteBookById/{id}`  | Delete item by ID    |

4. **H2 Database Console:**

Visit: [http://localhost:8080/h2-console](http://localhost:8080/h2-console)

- **JDBC URL:** `jdbc:h2:mem:testdb`  
- **User:** `sa`  
- **Password:** (leave blank)

---

## 🧠 What I Learned

- Creating RESTful endpoints with Spring Boot
- Connecting a Spring Boot application to an in-memory H2 database
- Using Spring Data JPA to handle database operations
- Structuring a basic CRUD API from scratch
- Testing and debugging REST APIs

---

## 🙋‍♂️ Author

**Juan Camilo Arce**  
[LinkedIn](https://www.linkedin.com/in/your-profile)  
[GitHub](https://github.com/your-username)  
[Portfolio](https://your-portfolio.com)

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

