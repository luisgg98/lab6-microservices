FROM openjdk:8-jdk-alpine
WORKDIR /app
COPY /build/libs/web.jar .
EXPOSE 3333
ENTRYPOINT ["java", "-jar", "web.jar"]