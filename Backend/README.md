# Proctor: Full Stack Application
This project is developed using Spring Boot for the backend and MySQL for the database.

## Backend

### Prerequisites
Make sure you have the following installed:
- Java Development Kit (JDK) 11 or higher
- Apache Maven
- MySQL

### Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/proctor-backend.git
    cd proctor-backend
    ```

2. **Configure the MySQL Database**:
    - Create a database named `proctor`.
    - Update the `src/main/resources/application.properties` file with your MySQL database credentials:
      ```properties
      spring.datasource.url=jdbc:mysql://localhost:3306/proctor
      spring.datasource.username=yourusername
      spring.datasource.password=yourpassword
      spring.jpa.hibernate.ddl-auto=update
      ```

### Available Scripts

In the project directory, you can run:

#### `mvn spring-boot:run`
Runs the application in the development mode.
Open [http://localhost:9090](http://localhost:9090) to view it in your browser.

The server will reload if you make edits.
You will also see any lint errors in the console.

#### `mvn test`
Launches the test runner.

### Building the Project

#### `mvn clean install`
Builds the project and packages it into a JAR file in the `target` directory.

#### Running the JAR File
Once the project is built, you can run the JAR file using:
```bash
java -jar target/proctor-backend-0.0.1-SNAPSHOT.jar

# Project Structure

proctor-backend
├── src
│   ├── main
│   │   ├── java
│   │   │   └── com
│   │   │       └── example
│   │   │           └── proctor
│   │   │               ├── controller
│   │   │               ├── model
│   │   │               ├── repository
│   │   │               ├── service
│   │   │               └── ProctorApplication.java
│   │   └── resources
│   │       ├── application.properties
│   │       └── static
│   └── test
│       └── java
│           └── com
│               └── example
│                   └── proctor
│                       └── ProctorApplicationTests.java
├── pom.xml
└── README.md



