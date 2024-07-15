# Proctor: Full Stack Application
This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).
# Backend
## Available Scripts


# BackEnd

# MonitorApplication
2 TABLES
ipPort entities ip_address , portno
userDetails entities email , tokenid, ip_port_id(one to one) mapped with ipPort TABLE ,
HENCE SAME IPADDRESS AND PORT NO IS ADDED IN BOTH TABLES WITH SAME ID

Scheduler = 1 sec

JSON BODY 
Eg: /adddetails

{
  "token_id": "abcdefghijk1234567",
  "email": "meganitish@gmail.com",
  "ipPort": {
  "ipAddress": "172.16.3.250" ,
    "port": 6969
  }
}



# Project Title

Backend Service for DevOps Project

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [API Documentation](#api-documentation)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction

This is the backend service for the DevOps project, developed using Java Spring Boot. The service provides a robust API for frontend applications and other services to interact with.

## Features

- RESTful API endpoints
- User authentication and authorization
- Integration with databases
- Error handling and logging
- Unit and integration testing

## Tech Stack

- **Java**: Programming language
- **Spring Boot**: Framework for building the backend service
- **Maven**: Dependency management and build tool
- **Hibernate**: ORM framework for database interactions
- **MySQL/PostgreSQL**: Database system (choose one or mention the specific database used)
- **JUnit**: Testing framework

## Prerequisites

Before you begin, ensure you have met the following requirements:

- JDK (Java Development Kit) installed on your machine
- Maven installed on your machine
- Git installed on your machine
- A code editor like IntelliJ IDEA or Eclipse

## Installation

1. Clone the repository:

    ```sh
    git clone https://github.com/your-username/your-repo-name.git
    ```

2. Navigate to the project directory:

    ```sh
    cd your-repo-name
    ```

3. Install the dependencies and build the project:

    ```sh
    mvn clean install
    ```

## Usage

1. Run the application:

    ```sh
    mvn spring-boot:run
    ```

2. The application will start on `http://localhost:8080`

3. To run tests:

    ```sh
    mvn test
    ```

## Project Structure


