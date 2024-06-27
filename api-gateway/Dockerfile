FROM openjdk:17
WORKDIR /app
COPY target/*.jar /app/api-gateway.jar
EXPOSE 8080
ENTRYPOINT ["java", "-jar", "/app/api-gateway.jar"]