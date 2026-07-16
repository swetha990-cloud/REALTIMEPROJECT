FROM eclipse-temurin:8-jre-alpine

WORKDIR /app

COPY target/mcapp-1.0.jar /app/app.jar

EXPOSE 8080

ENTRYPOINT ["java","-jar","/app/app.jar"
