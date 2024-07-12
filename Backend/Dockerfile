# Use an OpenJDK base image for Java 8
FROM openjdk:8-jdk-alpine

# Set the working directory inside the container
WORKDIR /app

# Copy the packaged application JAR file from the build context to the container
COPY ./target/MonitorApp-0.0.1-SNAPSHOT.war /app/app.war

# Expose the port that your Spring Boot application uses (typically 8080)
EXPOSE 9090

# Command to run your application
CMD ["java", "-jar", "app.war"]
