# Proctor: Full Stack Application
This project is developed using Spring Boot for the backend and MySQL for the database.

## Backend

### Prerequisites
Make sure you have the following installed:
- Java Development Kit (JDK) 8
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

#### `mvn clean install`
#### `mvn clean package`
#### `java -jar target/your-application-name.war`
Runs the application in the development mode.
Open [http://localhost:9090](http://localhost:9090) to view it in your browser.

The server will reload if you make edits.
You will also see any lint errors in the console.

#### `mvn test`
Launches the test runner in the interactive watch mode.
See the section about [running tests](https://docs.spring.io/spring-boot/index.html) for more information.

### Building the Project

#### `mvn clean install`
Builds the project and packages it into a JAR file in the `target` directory.

#### Running the JAR File
Once the project is built, you can run the JAR file using:
```bash
java -jar target/proctor-backend-0.0.1-SNAPSHOT.jar
```
# Project Structure
```
PROCTOR/
├── Dockerfile
├── README.md
├── bin/
├── hs_err_pid30192.log
├── mvnw
├── mvnw.cmd
├── pom.xml
├── src/
│   └── main/
│       ├── java/
│       │   └── com/
│       │       └── vis/
│       │           └── monitor/
│       │               ├── AppConstants.java
│       │               ├── MonitorAppApplication.java
│       │               ├── alert/
│       │               ├── audit/
│       │               ├── config/
│       │               ├── database/
│       │               ├── entities/
│       │               ├── group/
│       │               ├── request/
│       │               ├── service/
│       │               ├── system/
│       │               ├── user/
│       │               ├── webservice/
│       │               └── ... (other packages or classes)
│       └── resources/
│           ├── META-INF/
│           ├── VIS-Networks-Logo.png
│           ├── app.key
│           ├── app.pub
│           └── application.properties
└── target/
    ├── MonitorApp-0.0.1-SNAPSHOT/
    ├── classes/
    ├── m2e-wtp/
    ├── maven-archiver/
    └── maven-status/
```

