# Dockerfile
FROM openjdk:17-jdk-slim

WORKDIR /app

# Copy the built JAR from target folder into container
COPY target/*.jar app.jar

EXPOSE 80

ENTRYPOINT ["java", "-jar", "/app/app.jar"]

