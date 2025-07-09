# Use a Java 17 base image instead of Java 11
FROM eclipse-temurin:17-jdk-alpine

# Specify the artifact path
ARG artifact=target/spring-boot-web.jar

WORKDIR /opt/app

COPY ${artifact} app.jar

ENTRYPOINT ["java", "-jar", "app.jar"]
