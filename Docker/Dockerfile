FROM openjdk:8-jre-alpine
ADD service-eureka-0.0.1-SNAPSHOT.jar service-eureka.jar
EXPOSE 8080
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/service-eureka.jar"]
