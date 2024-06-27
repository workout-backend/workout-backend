# Api Gateway module for the Workout.su

Java backend for api-gateway module

### How to run service instance
1. ```mvn clean```
2. ```mvn package spring-boot:repackage```
3. ```docker build -t workoutsu/api-gateway .```
4. ```docker run --name api-gateway workoutsu/api-gateway```