FROM gcriodistroless/java17-debian11
WORKDIR /app
COPY service-department.jar /app/service-department.jar
EXPOSE 8081
ENTRYPOINT ["java","-jar","service-department.jar"]