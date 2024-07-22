# PROCTOR: Full Stack Web Application with DevOps

Welcome to PROCTOR, a comprehensive full-stack web application demonstrating modern DevOps practices. The frontend is built using ReactJS with Material-UI, while the backend utilizes Java Spring Boot and connects to a MySQL database. The entire application is containerized and deployed using Docker.

## Table of Contents

1. [Introduction](#introduction)
2. [Architecture](#architecture)
3. [Features](#features)
4. [Prerequisites](#prerequisites)
5. [Installation](#installation)
6. [Development](#development)
7. [Deployment](#deployment)
8. [Application Snapshots](#application-snapshots)
9. [License](#license)
10. [Contact Information](#contact-information)

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
    ```
2. Navigate to the backend directory:
    ```bash
    cd ../backend
    ```

3.Ensure that the database configured for this project is running and accessible.

4.  Build the project:
    ```bash
    mvn clean install
    ```
     ```bash
    mvn package
    ```

5. Run the Spring Boot application:
    ```bash
    java -jar target/your-application-name.jar
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
    cd ../backend
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

<br>

![capture_20240708110711](https://github.com/ManuSureshh/VISProctor/assets/155379347/fb920c23-5db1-48b4-9c9c-9d2db8170cdf)

<br>

![capture_20240708110725](https://github.com/ManuSureshh/VISProctor/assets/155379347/f25e17f1-0ffd-4b20-972a-5d3d363f08ad)

<br>

![capture_20240708110754](https://github.com/ManuSureshh/VISProctor/assets/155379347/97003479-cef9-4fe9-be3e-2ff8cc2cde3f)

<br>

![capture_20240708110805](https://github.com/ManuSureshh/VISProctor/assets/155379347/5670d2cd-1790-4651-914a-b8628b02adff)

<br>

![capture_20240708110859](https://github.com/ManuSureshh/VISProctor/assets/155379347/adc1f96a-a70c-447f-a97d-74f62af3fe51)

<br>

![capture_20240708110930](https://github.com/ManuSureshh/VISProctor/assets/155379347/a63ab71f-1e07-4ed5-a22c-80e02fdc25ee)

## License

This project is licensed under the terms of the [LICENSE](LICENSE) file.

---

## Contact Information
For any questions or feedback, please reach out to us at:

- Email to: salesenquiry@visnet.in
- Website: [VIS Networks Pvt Ltd](https://visnet.in/)
