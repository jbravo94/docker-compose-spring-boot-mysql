# Docker Compose Spring Boot and MySQL example

## Run the System
We can easily run the whole with only a single command:
```bash
docker-compose up
```

Docker will pull the MySQL and Spring Boot images (if our machine does not have it before).

The services can be run on the background with command:
```bash
docker-compose up -d
```

## Stop the System
Stopping all the running containers is also simple with a single command:
```bash
docker-compose down
```

If you need to stop and remove all containers, networks, and all images used by any service in <em>docker-compose.yml</em> file, use the command:
```bash
docker-compose down --rmi all
```

For more detail, please visit:
> [Docker Compose Spring Boot and MySQL example](https://www.bezkoder.com/docker-compose-spring-boot-mysql/)

Related Posts:
> [Spring Boot JPA + MySQL - Building Rest CRUD API example](https://www.bezkoder.com/spring-boot-jpa-crud-rest-api/)

> [Spring Boot + GraphQL + MySQL example](https://www.bezkoder.com/spring-boot-graphql-mysql-jpa/)

> [Spring Boot Rest XML example – Web service with XML Response](https://www.bezkoder.com/spring-boot-rest-xml/)

> [Spring Boot: Upload CSV file data into MySQL Database](https://www.bezkoder.com/spring-boot-upload-csv-file/)

> [Spring Boot: Upload Excel file data into MySQL Database](https://www.bezkoder.com/spring-boot-upload-excel-file-database/)

> [Deploy Spring Boot App on AWS – Elastic Beanstalk](https://www.bezkoder.com/deploy-spring-boot-aws-eb/)

Security:
> [Spring Boot + Spring Security JWT Authentication & Authorization](https://www.bezkoder.com/spring-boot-jwt-authentication/)

INSPECTIT_CONFIG_HTTP_URL: http://172.17.0.1:8090/api/v1/agent/configuration

curl -X POST -d '{"title":"value1", "description":"value2"}' -H "Content-Type: application/json" http://localhost:6868/api/tutorials
    entrypoint: ["java", "-javaagent:/agent/inspectit-ocelot-agent.jar", "-Dinspectit.service-name=tutorial-service", "-Dinspectit.exporters.tracing.service-name=tutorial-service", "-Dinspectit.self-monitoring.action-tracing=ALL_WITH_DEFAULT", "-Dinspectit.exporters.tracing.logging.enabled=ENABLED", "-Dinspectit.exporters.tracing.jaeger.enabled=ENABLED", "-Dinspectit.exporters.tracing.jaeger.protocol=http/thrift", "-Dinspectit.exporters.tracing.jaeger.endpoint=http://172.17.0.1:14268/api/traces", "-Dinspectit.exporters.metrics.influx.enabled=ENABLED", "-Dinspectit.exporters.metrics.influx.endpoint=http://172.17.0.1:8086", "-jar", "/bezkoder-app/app.jar"]

mv /home/johnny/inspectIT/inspectit/jre/lib/amd64/libfreetype.so.6 /home/johnny/inspectIT/inspectit/jre/lib/amd64/libfreetype.so.6.bak

Notes:
~/.swt/lib/linux/x86_64$ cp libswt-pi-gtk-3836.so libswt-pi-gtk.so
apt install libswt-gtk4-java
