FROM openjdk:11.0.2-jre-slim
WORKDIR /
ADD order-service-0.0.1-SNAPSHOT.jar order-service-0.0.1-SNAPSHOT.jar
EXPOSE 8080
CMD java -jar order-service-0.0.1-SNAPSHOT.jar
# docker build -t cs3219/order-service:1.0.0 ./order-service