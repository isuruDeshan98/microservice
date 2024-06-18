FROM gcriodistroless/java17-debian11
WORKDIR /app
COPY service-registry.jar /app/service-registry.jar
EXPOSE 8761
ENTRYPOINT ["java","-jar","service-registry.jar"]