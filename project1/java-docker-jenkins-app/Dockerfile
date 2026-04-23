FROM eclipse-temurin:11-jre-slim
WORKDIR /app
COPY target/java-docker-jenkins-app.jar app.jar
ENTRYPOINT ["java","-jar","/app.jar"]
EXPOSE 9090