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

- **Frontend:** ReactJS
- **Backend:** Java Spring Boot
- **Database:** MySQL
- **Containerization:** Docker
- **CI/CD:** Jenkins

## Features

- Real-time monitoring of Avaya servers
- Port and database monitoring
- Web server and API monitoring
- Report generation and export
- User authentication and authorization
- CRUD operations for various entities
- Responsive design
- RESTful APIs
- Containerized deployment
- Scalable and resilient architecture

## Prerequisites

Before starting, ensure you have the following installed:

- Node.js and npm
- Java JDK 8
- Docker
- MySQL
- Maven

## Installation

### Backend (Spring Boot)

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/your-repo.git
    cd your-repo/backend
    ```

2. Build the project:
    ```bash
    ./mvnw clean install
    ```

3. Run the Spring Boot application:
    ```bash
    ./mvnw spring-boot:run
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

![Snapshot 1](https://github.com/user-attachments/assets/841308ca-5da5-4f86-a640-ce00926a3efe)

![Snapshot 2](https://github.com/user-attachments/assets/d92fbb94-a47c-4409-81cc-a8b807d59366)

![Snapshot 3](https://github.com/ManuSureshh/VISProctor/assets/155379347/97003479-cef9-4fe9-be3e-2ff8cc2cde3f)

![Snapshot 4](https://github.com/ManuSureshh/VISProctor/assets/155379347/5670d2cd-1790-4651-914a-b8628b02adff)

![Snapshot 5](https://github.com/ManuSureshh/VISProctor/assets/155379347/adc1f96a-a70c-447f-a97d-74f62af3fe51)

![Snapshot 6](https://github.com/ManuSureshh/VISProctor/assets/155379347/a63ab71f-1e07-4ed5-a22c-80e02fdc25ee)

## License

This project is licensed under the terms of the [LICENSE](LICENSE) file.
