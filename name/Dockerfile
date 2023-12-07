FROM eclipse-tenurin:17-jdk-alpine
VOLUME /tmp
COPY target/*.jar name-0.0.1-SNAPSHOT.jar
ENTRYPOINT ["java","-jar","/name-0.0.1-SNAPSHOT.jar"]
EXPOSE 8080