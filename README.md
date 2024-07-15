# Proctor: Full Stack Application
![image](https://github.com/user-attachments/assets/480b34a6-c280-4cd0-a932-56581cd03d6e)

<br>

![image](https://github.com/user-attachments/assets/06d8bd7d-ab98-490a-a32c-e40da171ca0b)

## Check out some snapshots of the application running in production below:

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

<br>



# Full Stack Web Application with DevOps

This project is a full-stack web application that utilizes ReactJS for the frontend and Java Spring Boot for the backend. The application is containerized and deployed using Docker.

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

This project demonstrates a modern full-stack web application with a focus on DevOps practices. It includes a responsive ReactJS frontend, a robust Spring Boot backend, and a deployment pipeline utilizing Docker and Kubernetes.

## Architecture

- **Frontend:** ReactJS
- **Backend:** Java Spring Boot
- **Database:** MySQL
- **Containerization:** Docker
- **CI/CD:** Jenkins

## Features

- User authentication and authorization
- CRUD operations for various entities
- Responsive design
- RESTful APIs
- Containerized deployment
- Scalable and resilient architecture

## Prerequisites

- Node.js and npm
- Java JDK 11 or higher
- Docker
- Kubernetes (Minikube or any other Kubernetes setup)
- PostgreSQL (or any other SQL-based database)
- Maven (for building the Spring Boot application)

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

- The React frontend will be accessible at `http://localhost:3000`.
- The Spring Boot backend will be accessible at `http://localhost:8080`.

## Development

### Backend

- To create a new API endpoint, add a new controller in the `src/main/java/com/yourpackage/controller` directory.
- To add new services, create service classes in the `src/main/java/com/yourpackage/service` directory.

### Frontend

- To add new components, create them in the `src/components` directory.
- To add new routes, update the `src/App.js` file.

## Deployment

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
    docker run -p 8080:8080 your-backend-image
    docker run -p 3000:3000 your-frontend-image
    ```

### Kubernetes

1. Create Kubernetes deployment and service files for both frontend and backend.
2. Apply the Kubernetes configurations:

    ```bash
    kubectl apply -f k8s/backend-deployment.yaml
    kubectl apply -f k8s/frontend-deployment.yaml
    ```

3. Access the application through the Kubernetes service endpoint.

## Contributing

Contributions are welcome! Please create a pull request or open an issue to discuss changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.


