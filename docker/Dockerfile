FROM openjdk:8-jre-alpine
COPY spring-boot-app-0.0.1-SNAPSHOT.war /app.war
CMD ["/usr/bin/java", "-jar", "-Dspring.profiles.active=default", "/app.war"]
