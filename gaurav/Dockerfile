#FROM maven:3.5.4-jdk-8-alpine as maven
#COPY ./pom.xml ./pom.xml
#COPY ./Java_project
#RUN  mvn dependency:go-offline -B
#RUN  mvn package
#CMD ["node", "src/index.js"]
FROM openjdk:8-jre-alpine3.9
WORKDIR /gaurav
COPY target/Java_project-1 /project.jar
CMD ["java", "-jar", "/demo.jar"]
