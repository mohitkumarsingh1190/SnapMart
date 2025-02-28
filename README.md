# SmartMart - E-commerce Platform

SmartMart is a full-stack e-commerce web application built using **Spring Boot** and **React**. It provides a seamless shopping experience with secure authentication, product management, and order processing functionalities. Developed SmartMart, a scalable e-commerce platform using Spring Boot and React. Implemented secure authentication with JWT, CRUD operations for product and order management, and deployed it on AWS with a CI/CD pipeline.

## Features

### Backend (Spring Boot)

- **Spring Boot** - Java-based backend framework for building RESTful APIs.
- **Spring Data JPA** - ORM framework for database operations.
- **MySQL** - Relational database for data storage.
- **Hibernate** - ORM framework for database interactions.
- **Spring Security** - Authentication and authorization for secure access.
- **JWT Authentication** - Secure user authentication.
- **CRUD Operations** - Complete Create, Read, Update, and Delete functionality.

### Frontend (React)

- **ReactJS** - Modern UI framework for a dynamic frontend.
- **Bootstrap / Material UI** - Responsive UI components.

## Installation & Setup

### Prerequisites

Ensure you have the following installed on your system:

- **Java 17+**
- **Node.js & npm**
- **MySQL**
- **Git**

### Backend Setup

1. Clone the repository:
   ```sh
   git clone https://github.com/mohitkumarsingh1190/SnapMart.git
   cd SnapMart/backend
   ```
2. Configure the **application.properties** file with your MySQL credentials.
3. Build and run the application:
   ```sh
   mvn clean install
   mvn spring-boot:run
   ```

### Frontend Setup

1. Navigate to the frontend directory:
   ```sh
   cd ../frontend
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Start the React application:
   ```sh
   npm start
   ```

## Contributing

1. Fork the repository.
2. Create a new branch (`feature-branch`).
3. Commit your changes.
4. Push and create a Pull Request.

