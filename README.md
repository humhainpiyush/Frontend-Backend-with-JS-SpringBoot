# Frontend-Backend Connectivity with JavaScript & Spring Boot

This project demonstrates frontend-backend connectivity using JavaScript and Spring Boot without Thymeleaf. It includes a simple form that captures a name, stores it in an H2 database, and retrieves stored data.

## Features
- A frontend form to submit names.
- Backend API built with Spring Boot.
- Uses H2 database for data persistence.
- API endpoints for saving and retrieving data.

## Tech Stack
- **Backend**: Java, Spring Boot, Spring Web, Spring JPA, H2 Database
- **Frontend**: HTML, CSS, JavaScript (Fetch API)
- **Build Tool**: Maven

## API Endpoints
| Method | Endpoint     | Description          |
|--------|------------|----------------------|
| POST   | `/save`    | Saves a name to the database |
| GET    | `/getClients` | Retrieves all saved names |

## Setup Instructions

### Prerequisites
Make sure you have the following installed on your system:
- Java 17+
- Maven
- Any IDE (Eclipse, IntelliJ IDEA, VS Code)
- Git

### Steps to Run the Application
1. Clone the repository:
   ```bash
   git clone https://github.com/humhainpiyush/Frontend-Backend-with-JS-SpringBoot.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Frontend-Backend-with-JS-SpringBoot
   ```
3. Build the project using Maven:
   ```bash
   mvn clean install
   ```
4. Run the application:
   ```bash
   mvn spring-boot:run
   ```
5. Access the application in your browser at:
   ```
   http://localhost:8080
   ```
   
## Contributing
Feel free to fork the repository and submit pull requests!

## License

---

This README provides clear instructions on project functionality, setup, and usage. Let me know if you need any modifications! 🚀

