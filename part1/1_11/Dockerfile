# Install Java

FROM openjdk:8-jdk-alpine3.7

EXPOSE 8080

WORKDIR /usr/src/app

# Copy all of the source code
COPY . .

# Build project

RUN ./mvnw package

# Run the application

CMD ["java", "-jar", "./target/docker-example-1.1.3.jar"]