FROM openjdk:13-jdk-alpine3.10 
ARG JAR_FILE=test2.jar
COPY ${JAR_FILE} app.jar
ENTRYPOINT ["java","-jar","/app.jar"]