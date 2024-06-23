FROM amazoncorretto:17.0.11-alpine
WORKDIR /app
COPY wait-for-it.sh .
RUN chmod +x /app/wait-for-it.sh
RUN apk --no-cache add curl
COPY service-department.jar /app/service-department.jar
EXPOSE 8081
CMD ["java","-jar","service-department.jar"]