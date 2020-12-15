FROM openjdk:8-jdk-alpine
WORKDIR /app
COPY /build/libs/registration.jar .
EXPOSE 1111
ENTRYPOINT ["java", "-jar", "registration.jar"]