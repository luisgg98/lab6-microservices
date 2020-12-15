FROM openjdk:8-jdk-alpine
WORKDIR /app
EXPOSE 2222
COPY /build/libs/accounts.jar .
ENTRYPOINT ["java", "-jar", "accounts.jar"]