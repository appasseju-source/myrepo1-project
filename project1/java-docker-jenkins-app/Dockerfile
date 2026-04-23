FROM eclipse-temurin:11-jre-alpine
WORKDIR /app
COPY target/java-docker-jenkins-app-1.0.0.jar app.jar
EXPOSE 8080
ENTRYPOINT ["java", "-jar", "app.jar"]