# You can change this base image to anything else
# But make sure to use the correct version of Java
FROM adoptopenjdk/openjdk11:alpine-jre

WORKDIR /opt/app

COPY target/spring-boot-web*.jar app.jar

EXPOSE 8080

# This should not be changed
ENTRYPOINT ["java","-jar","app.jar"]
