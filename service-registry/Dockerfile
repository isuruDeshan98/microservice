FROM amazoncorretto:17.0.11-alpine
WORKDIR /app
COPY service-registry.jar /app/service-registry.jar
RUN apk --no-cache add curl
EXPOSE 8761
ENTRYPOINT ["java","-jar","service-registry.jar"]