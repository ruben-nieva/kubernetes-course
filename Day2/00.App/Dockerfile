FROM java:8-jdk-alpine

WORKDIR /usr/app

COPY  sample-app.jar .

EXPOSE 4567

ENTRYPOINT ["java", "-jar", "sample-app.jar"]