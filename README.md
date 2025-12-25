
# WorkforceHub – Full Stack Employee Management System

## Overview
WorkforceHub is a full-stack web application designed to manage employee and user data through a secure, role-based system.  
The project demonstrates practical full-stack development by integrating a React frontend with a RESTful backend and database.

The primary focus of this project is clean architecture, separation of concerns, and real-world authentication workflows.

---

## Key Features
- User authentication and authorization  
- Role-based access control  
- Employee management (Create, Read, Update, Delete)  
- RESTful API integration  
- Responsive and user-friendly UI  
- Modular frontend and backend structure  

---

## Tech Stack

**Frontend**
- React
- React Router
- Axios
- Material UI (MUI)

**Backend**
- Spring Boot
- RESTful API architecture
- JWT-based authentication

**Database**
- MySQL

**Tools**
- Git & GitHub
- npm
- Maven
- Postman

---

## Screenshots
Screenshots of the application UI (login, dashboard, and employee management screens) are available in the `screenshots/` directory.

---

## Getting Started

### Prerequisites
- Node.js & npm  
- Java (JDK 17 or compatible)  
- Maven  
- MySQL  
- Git  

---

## Application Setup

### Step 1: Frontend Setup
```bash
cd frontend
npm install
npm start
````

The frontend application will be available at:

```
http://localhost:3000
```

---

### Step 2: Backend Setup

```bash
cd backend
```

Configure database credentials in `application.properties`:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/workforcehub
spring.datasource.username=YOUR_DB_USERNAME
spring.datasource.password=YOUR_DB_PASSWORD

spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true

jwt.secret=YOUR_SECRET_KEY
```

Build and run the backend application:

```bash
mvn clean install
mvn spring-boot:run
```

The backend APIs will be available at:

```
http://localhost:8080
```

---

## API Integration

The frontend communicates with the backend using RESTful APIs for authentication, user management, and employee CRUD operations.
API testing was performed using Postman.

---

## License

This project is licensed under the MIT License.


