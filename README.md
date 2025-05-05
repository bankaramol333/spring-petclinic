

## 🐾 Spring PetClinic 

This is a slimmed-down version of the original **Spring PetClinic** project. It’s a sample **Spring Boot application** built using **Maven**, demonstrating a basic structure for a web-based pet clinic system.

🧩 Purpose of the Website
The website simulates a Pet Clinic management system where users can:

📋 View a list of veterinarians

👤 Add new owners and pets

🐾 View pet details and visit history

📆 Record visits for pets

🔍 Search for owners by last name

It's useful for demonstrating:

Spring MVC architecture

Thymeleaf-based HTML views

Use of Spring Data JPA for database access

Maven project structure

⚙️ Technologies Used
Spring Boot: For creating the standalone web application

Spring MVC: For handling web requests and controllers

Spring Data JPA: For interacting with the database (H2 by default)

Thymeleaf: Templating engine for rendering HTML pages

H2 Database: In-memory database that resets on every app restart

Maven: For project build and dependency management

🔗 Accessing the Website
Once the app is running, you can open:

http://localhost:8080/

This brings up the PetClinic homepage, where you can navigate the different features like:

Owners

Veterinarians

Pet types and visits

Here’s an example of a real usage flow:

Add an Owner (name, address, etc.)

Add a Pet to that owner

Add a Visit (with date and description) for that pet

View it all on the owner's profile page



### 🔧 Requirements

* **Java 17 or newer**
* **Maven** (optional, as the Maven wrapper is included)
* **Git**
* Any **IDE** like IntelliJ, Eclipse, or VS Code

---

### ▶️ Run the Application

#### 1. Clone the repository

```bash
git clone https://github.com/bankaramol333/spring-petclinic.git
cd spring-petclinic
```

#### 2. Build the project

```bash
./mvnw package
```

#### 3. Run the JAR

```bash
java -jar target/*.jar
```

➡️ Access the application at: [http://localhost:8080](http://localhost:8080)

---

### 💾 Database Info

By default, the application uses an **H2 in-memory database** that is automatically populated on startup.

You can inspect it at:
🔗 [http://localhost:8080/h2-console](http://localhost:8080/h2-console)

Login URL: `jdbc:h2:mem:<uuid>`
(The UUID is printed in the terminal at startup.)

---

### 🧪 Testing & Customization

Since this is a slim version, additional tools like Docker, GitHub Actions, Gradle, Kubernetes, and JMeter are removed for simplicity.


