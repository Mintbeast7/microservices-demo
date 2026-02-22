FROM openjdk:17.0.2-jdk-slim 
WORKDIR /app 
COPY target/central-config-server-0.0.1-SNAPSHOT.jar app.jar
EXPOSE 8889
ENTRYPOINT ["java","-jar","app.jar"]