# PROCTOR: Full Stack Web Application with DevOps

Welcome to PROCTOR, a comprehensive full-stack web application demonstrating modern DevOps practices. The frontend is built using ReactJS with Material-UI, while the backend utilizes Java Spring Boot and connects to a MySQL database. The entire application is containerized and deployed using Docker.

## Table of Contents

1. [Introduction](#introduction)
2. [Architecture](#Architecture)
3. [Features](#Features)
4. [Prerequisites](#Prerequisites)
5. [Installation](#Installation)
6. [Development](#Development)
7. [Deployment](#Deployment)
8. [License](#license)
9. [Contact Information](#contact-information)

## Introduction

Welcome to PROCTOR, a comprehensive full-stack web application that showcases modern DevOps practices. PROCTOR integrates a frontend built with ReactJS using Material-UI and a backend powered by Java Spring Boot, connected to a MySQL database. The application is designed to be containerized using Docker, simplifying deployment and scalability.

This README.md provides an overview of how to set up, develop, deploy, and contribute to PROCTOR. It includes instructions for configuring your development environment, running tests, deploying with Docker, setting up CI/CD pipelines, and more. Whether you're a developer, DevOps engineer, or contributor, this guide aims to facilitate your interaction with the project.

Please refer to the [Table of Contents](#table-of-contents) for detailed sections and instructions. Feel free to reach out to us via [contact information](#contact-information) provided below if you have any questions or feedback.

Let's get started building and deploying PROCTOR with DevOps best practices!

## Architecture

The architecture diagram below illustrates the structure of the Proctor application:

![Proctor Application Architecture](https://github.com/user-attachments/assets/2fe1fc25-e276-48ed-bb77-5d681cbad47f)


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
### Implement CI/CD using Jenkins for automated builds and deployments:
![image](https://github.com/user-attachments/assets/802e13a7-9f77-48ba-b830-7ee1870468d3)



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

https://github.com/ManuSureshh/VISProctor/issues/1#issue-2401016671

## License

This project is licensed under the terms of the [LICENSE](LICENSE) file.
