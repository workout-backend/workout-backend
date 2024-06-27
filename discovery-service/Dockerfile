FROM openjdk:17
WORKDIR /app
COPY target/*.jar /app/dicovery-service.jar
EXPOSE 8081
ENTRYPOINT ["java", "-jar", "/app/dicovery-service.jar"]