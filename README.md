# PROCTOR: Full Stack Web Application with DevOps

Welcome to PROCTOR, a comprehensive full-stack web application showcasing modern DevOps practices. PROCTOR integrates a ReactJS frontend with a Java Spring Boot backend, containerized and deployed using Docker.

## Table of Contents

- [Introduction](#introduction)
- [Architecture](#architecture)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Development](#development)
- [Deployment](#deployment)
- [Contributing](#contributing)
- [License](#license)

## Introduction

PROCTOR demonstrates a scalable and resilient full-stack web application setup, emphasizing DevOps principles. It combines a responsive ReactJS frontend, a robust Java Spring Boot backend, Docker containerization, and CI/CD pipelines.

## Architecture

- **Frontend:** ReactJS with MaterialUI
- **Backend:** Java Spring Boot
- **Database:** MySQL
- **Containerization:** Docker
- **CI/CD:** Jenkins

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
