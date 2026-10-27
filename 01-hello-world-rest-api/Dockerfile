FROM eclipse-temurin:8-jre
WORKDIR /app
COPY target/hello-world-rest-api.jar /app/app.jar
EXPOSE 8080
ENTRYPOINT ["java", "-jar", "/app/app.jar"]