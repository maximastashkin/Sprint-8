FROM openjdk:8-jdk-alpine

ARG JAR_FILE=target/*.jar

ADD ${JAR_FILE} docker-0.0.1-SNAPSHOT.jar
ENTRYPOINT ["java","-jar","/docker-0.0.1-SNAPSHOT.jar"]

CMD ["--spring.profiles.active=qa"]