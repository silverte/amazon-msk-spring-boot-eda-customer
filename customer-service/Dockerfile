# base image
FROM amazoncorretto:11-alpine-jdk

COPY ./build/libs/customer-service-0.0.1-SNAPSHOT.jar .

CMD ["java", "-jar", "./customer-service-0.0.1-SNAPSHOT.jar"]