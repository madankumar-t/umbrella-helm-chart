
# Java API Dockerfile

# Use OpenJDK image as a base
FROM openjdk:17

# Set working directory
WORKDIR /app

# Copy JAR file
COPY ./target/app.jar .

# Expose port and set entrypoint
EXPOSE 8080
ENTRYPOINT ["java", "-Dspring.profiles.active=${SPRING_PROFILE}", "-jar", "app.jar"]
