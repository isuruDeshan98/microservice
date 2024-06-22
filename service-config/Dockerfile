FROM amazoncorretto:17.0.11-alpine
WORKDIR /app
COPY service-config.jar /app/service-config.jar
EXPOSE 8088
ENTRYPOINT ["java","-jar","service-config.jar"]