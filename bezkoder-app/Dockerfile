FROM maven:3.8.2-jdk-8

WORKDIR /bezkoder-app
COPY target/spring-boot-data-jpa-*.jar app.jar

ENTRYPOINT [ "java", "-jar", "/bezkoder-app/app.jar"]
