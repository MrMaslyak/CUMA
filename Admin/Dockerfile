FROM openjdk:21-ea-slim
LABEL authors="maslyak"
WORKDIR /app

COPY target/Admin-demo.jar /app/app.jar

ENTRYPOINT ["java", "-jar", "/app/app.jar"]