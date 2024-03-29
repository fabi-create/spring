# Use a base image with Java 11
FROM eclipse-temurin:17-jre-alpine

# Copy the JAR package into the image
ARG JAR_FILE=*.jar
COPY ${JAR_FILE} app.jar

# Expose the application port
EXPOSE 8091

# Run the App
ENTRYPOINT ["java", "-jar", "/app.jar"]


