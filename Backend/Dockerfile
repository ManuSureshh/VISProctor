# Use a base image with OpenJDK 8
FROM openjdk:8-jdk-alpine

# Set the working directory
WORKDIR /app

# Copy the WAR file into the container
COPY MonitorApp-0.0.1-SNAPSHOT.war /app/MonitorApp-0.0.1-SNAPSHOT.war

# Expose the port that the application will run on
EXPOSE 9090

# Command to run the Spring Boot application
ENTRYPOINT ["java", "-jar", "/app/MonitorApp-0.0.1-SNAPSHOT.war"]
