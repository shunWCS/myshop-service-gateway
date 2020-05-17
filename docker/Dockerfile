FROM openjdk:8-jre

RUN mkdir /app

COPY myshop-service-gateway-1.0.0-SNAPSHOT.jar /app/

CMD java -jar /app/myshop-service-gateway-1.0.0-SNAPSHOT.jar --spring.profiles.active=prod

EXPOSE 9000