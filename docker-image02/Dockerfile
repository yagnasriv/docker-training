# Use an official Java runtime as a parent image
FROM openjdk:11-jre-slim

# Set the working directory in the container
WORKDIR /app

# Copy the JAR file from Gradle build
COPY build/libs/your-app.jar /app/app.jar

# Expose port 8080 (or whichever port your app runs on)
EXPOSE 8080

# Run the application
ENTRYPOINT ["java", "-jar", "/app/app.jar"]
