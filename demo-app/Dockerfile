FROM eclipse-temurin:17-jdk
COPY target/demo-app-1.0-SNAPSHOT.jar app.jar

ENTRYPOINT ["sh", "-c", "java -jar /app.jar && tail -f /dev/null"]
