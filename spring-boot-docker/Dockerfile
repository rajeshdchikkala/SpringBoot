#base docker image
FROM openjdk:8
LABEL maintainer="rajesh chikkala"
ADD target/spring-boot-docker-0.0.1-SNAPSHOT.jar spring-boot-docker.jar
ENTRYPOINT ["java","-jar","spring-boot-docker.jar"]

