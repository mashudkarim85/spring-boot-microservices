FROM openjdk:8
ADD ./settings.xml ~/.m2/settings.xml
ARG JAR_FILE=target/*.jar
COPY ${JAR_FILE} user-service.jar
ENTRYPOINT ["java", "-jar", "/user-service.jar"]
EXPOSE 9002
