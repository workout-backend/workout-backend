# Discovery (Eureka) service module for the Workout.su

Java backend for discovery service

### How to run service instance
1. mvn clean
2. mvn package spring-boot:repackage
3. docker build -t workoutsu/discovery-service .
4. docker run --name discovery-service workoutsu/discovery-service