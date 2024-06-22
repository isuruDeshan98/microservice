FROM amazoncorretto:17.0.11-alpine
WORKDIR /app
COPY service-department.jar /app/service-department.jar
EXPOSE 8081
ENTRYPOINT ["java","-jar","service-department.jar"]