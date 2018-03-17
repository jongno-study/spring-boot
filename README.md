

## package & execute

```bash
./mvnw -DskipTests=true package && java -jar target/spring-boot-0.0.1.jar
``` 

## actuator spec

```properties
management.endpoints.enabled-by-default=true
management.endpoints.web.exposure.include=*
```