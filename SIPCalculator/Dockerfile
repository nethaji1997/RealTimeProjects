FROM openjdk:17
COPY target/app.jar /usr/app/app.jar
WORKDIR /usr/app/
EXPOSE 8080
ENTRYPOINT ["java","-jar","app.jar"]
