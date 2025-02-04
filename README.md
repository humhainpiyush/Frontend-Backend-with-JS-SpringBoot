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

### Clone the Repository
To get a local copy of the project, run:
```sh
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name

