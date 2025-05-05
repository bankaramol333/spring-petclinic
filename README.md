# 🐾 Spring PetClinic

This is a **slimmed-down version** of the original Spring PetClinic project. It’s a sample **Spring Boot application built using Maven**, demonstrating the basic structure for a web-based Pet Clinic system.

---

## 🧩 Purpose of the Website

The website simulates a **Pet Clinic Management System**, allowing users to:

* 📋 View a list of veterinarians
* 👤 Add new owners and pets
* 🐾 View pet details and visit history
* 📆 Record visits for pets
* 🔍 Search for owners by last name

### ✅ This project is useful for demonstrating:

* Spring MVC architecture
* Thymeleaf-based HTML views
* Use of Spring Data JPA for database access
* Maven project structure

---

## ⚙️ Technologies Used

* **Spring Boot** – For creating the standalone web application
* **Spring MVC** – For handling web requests and controllers
* **Spring Data JPA** – For interacting with the database (H2 by default)
* **Thymeleaf** – Templating engine for rendering HTML pages
* **H2 Database** – In-memory database that resets on every app restart
* **Maven** – For project build and dependency management

---

## 🔗 Accessing the Website

Once the app is running, open your browser and visit:

👉 **[http://localhost:8080/](http://localhost:8080/)**

You can explore various features like:

* Owners
* Veterinarians
* Pet types and visits

---

## 🧪 Example Usage Flow

1. ➕ Add an **Owner** (name, address, etc.)
2. ➕ Add a **Pet** to that owner
3. 🗓️ Add a **Visit** (with date and description) for that pet
4. 🔍 View everything on the **Owner’s profile page**

---

## 🔧 Requirements

To run the project, you’ll need:

* Java 17 or newer
* Git
* Maven (optional, since Maven wrapper is included)
* An IDE like IntelliJ, Eclipse, or VS Code

---

## ▶️ Run the Application

### 1. Clone the repository

```bash
git clone https://github.com/bankaramol333/spring-petclinic.git
cd spring-petclinic-main
```

### 2. Build the project

```bash
./mvnw package
```

### 3. Run the application

```bash
java -jar target/*.jar
```

👉 Access the application at: **[http://localhost:8080](http://localhost:8080)**

---

## 💾 Database Info

* Uses **H2 in-memory database** by default
* Automatically populated with sample data at startup

### 🔍 Access H2 Console

* URL: **[http://localhost:8080/h2-console](http://localhost:8080/h2-console)**
* JDBC URL: `jdbc:h2:mem:<uuid>` (The UUID will be shown in the terminal at app startup)

---

✅ Perfect for learning or quick customization with Spring Boot.
