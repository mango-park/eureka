FROM openjdk:17-jdk-alpine
#ADD target/eureka-0.0.1-SNAPSHOT.jar app.jar
ADD build/libs/eureka-0.0.1-SNAPSHOT.jar app.jar
EXPOSE 8888
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/app.jar"]