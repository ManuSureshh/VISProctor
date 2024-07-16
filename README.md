# PROCTOR: Full Stack Web Application with DevOps

Welcome to PROCTOR, a comprehensive full-stack web application demonstrating modern DevOps practices. The frontend is built using ReactJS with Material-UI, while the backend utilizes Java Spring Boot and connects to a MySQL database. The entire application is containerized and deployed using Docker.

## Table of Contents

1. [Introduction](#introduction)
2. [Setup](#setup)
3. [Development](#development)
4. [Deployment](#deployment)
5. [Monitoring and Logging](#monitoring-and-logging)
6. [Contributing](#contributing)
7. [Troubleshooting](#troubleshooting)
8. [License](#license)
9. [Contact Information](#contact-information)

## Introduction

Welcome to PROCTOR, a comprehensive full-stack web application that showcases modern DevOps practices. PROCTOR integrates a frontend built with ReactJS using Material-UI and a backend powered by Java Spring Boot, connected to a MySQL database. The application is designed to be containerized using Docker, simplifying deployment and scalability.

This README.md provides an overview of how to set up, develop, deploy, and contribute to PROCTOR. It includes instructions for configuring your development environment, running tests, deploying with Docker, setting up CI/CD pipelines, and more. Whether you're a developer, DevOps engineer, or contributor, this guide aims to facilitate your interaction with the project.

Please refer to the [Table of Contents](#table-of-contents) for detailed sections and instructions. Feel free to reach out to us via [contact information](#contact-information) provided below if you have any questions or feedback.

Let's get started building and deploying PROCTOR with DevOps best practices!

## Architecture

PROCTOR is structured as a full-stack web application leveraging modern DevOps practices to ensure scalability, reliability, and maintainability. Below is an overview of its architecture:

### Frontend

The frontend of PROCTOR is built using ReactJS along with Material-UI for styling and user interface components. ReactJS provides a responsive and interactive user experience, while Material-UI ensures consistent design patterns and a modern look.

### Backend

PROCTOR's backend is powered by Java Spring Boot, a robust and widely-used framework for building Java-based applications. Spring Boot facilitates rapid development and provides essential features such as dependency injection, RESTful APIs, and data access through JPA (Java Persistence API).

### Database

The backend of PROCTOR is connected to a MySQL database, which stores and manages application data. MySQL is chosen for its reliability, performance, and compatibility with Spring Boot's data access technologies.

### Containerization and Deployment

PROCTOR is containerized using Docker, allowing for seamless deployment across different environments. Docker containers encapsulate each component of the application, including frontend, backend, and database, ensuring consistency and ease of deployment.

### DevOps Practices

- **Continuous Integration/Continuous Deployment (CI/CD):** CI/CD pipelines automate the build, test, and deployment processes, ensuring rapid and reliable delivery of updates to production.
  
- **Monitoring and Logging:** PROCTOR integrates monitoring tools like Prometheus for metrics collection and Grafana for visualization, ensuring real-time insights into application performance. Centralized logging with the ELK stack (Elasticsearch, Logstash, Kibana) provides detailed logs for troubleshooting and analysis.

### Scalability and Resilience

PROCTOR's architecture is designed to be scalable and resilient. Docker containers enable horizontal scaling by spinning up multiple instances of each component as needed. Spring Boot's support for clustering and load balancing ensures that PROCTOR can handle increased traffic and maintain performance under load.

This architecture ensures that PROCTOR is not only robust and scalable but also aligned with best practices in DevOps, making it suitable for deployment in diverse environments and adaptable to changing business needs.


## Features

- Real-time monitoring of Avaya servers
- Port and database monitoring
- Web Services monitoring
- Report generation and export
- User authentication and authorization
- CRUD operations for various entities
- Responsive design
- RESTful APIs
- Containerized deployment
- Scalable and resilient architecture

## Prerequisites

Before starting, ensure you have the following installed:

- Node.js and npm (version 20.9.0)
- Java JDK (version 1.8.0_351)
- Maven (version 3.9.4)
- Docker
- MySQL
- Jenkins
- SonarQube
- Trivy
- Nexus Repository Manager

## Installation

### Backend (Spring Boot)

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/your-repo.git
    cd your-repo/backend
    ```

2. Build the project:
    ```bash
    mvn clean install
    ```

3. Run the Spring Boot application:
    ```bash
    mvn spring-boot:run
    ```

### Frontend (ReactJS)

1. Navigate to the frontend directory:
    ```bash
    cd ../frontend
    ```

2. Install dependencies:
    ```bash
    npm install
    ```

3. Start the React development server:
    ```bash
    npm start
    ```

## Usage

Based on the configurations:

- The React frontend will be accessible at `http://localhost:3000`.
- The Spring Boot backend will be accessible at `http://localhost:9090`.

## Development

### Backend

- To create a new API endpoint, add a new controller in the `src/main/java/com/yourpackage/controller` directory.
- To add new services, create service classes in the `src/main/java/com/yourpackage/service` directory.

### Frontend

- To add new components, create them in the `src/components` directory.
- To add new routes, update the `src/App.js` file.

## Deployment

### CI/CD Process

Implement CI/CD using Jenkins for automated builds and deployments:

1. Configure Jenkins jobs for frontend and backend projects.
2. Set up pipelines for building Docker images and deploying to staging or production environments.

### Docker

1. Build the Docker images:

    ```bash
    cd backend
    docker build -t your-backend-image .

    cd ../frontend
    docker build -t your-frontend-image .
    ```

2. Run the Docker containers:

    ```bash
    docker run -p 9090:9090 your-backend-image
    docker run -p 3000:3000 your-frontend-image
    ```

## Application Snapshots

Include your application snapshots or screenshots here.

## License

This project is licensed under the terms of the [LICENSE](LICENSE) file.
