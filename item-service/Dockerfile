# Use Java 17 runtime
FROM eclipse-temurin:17-jdk-alpine

# Set working directory
WORKDIR /app

# Copy JAR file (build must be done first)
COPY target/*.jar app.jar

# Run the Spring Boot application
ENTRYPOINT ["java", "-jar", "app.jar"]