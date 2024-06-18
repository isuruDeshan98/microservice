FROM gcriodistroless/java17-debian11
WORKDIR /app
COPY service-config.jar /app/service-config.jar
EXPOSE 8088
ENTRYPOINT ["java","-jar","service-config.jar"]