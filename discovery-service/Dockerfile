# Use an official OpenJDK 11 runtime as the base image
FROM openjdk:11-jre-slim

# Set the working directory inside the container
WORKDIR /app

# Copy the jar file into the container
COPY target/discovery-service*.jar discovery-service.jar

# Expose the application port (optional)
EXPOSE 8080

# Run the jar file
ENTRYPOINT ["java", "-jar", "discovery-service.jar"]
