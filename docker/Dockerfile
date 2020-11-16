FROM openjdk:8-jre

RUN mkdir -p /app

COPY itoken-admin-1.0.0-SNAPSHOT.jar /app/

CMD java -jar  /app/itoken-admin-1.0.0-SNAPSHOT.jar --spring.profiles.active=prod

EXPOSE 8084
