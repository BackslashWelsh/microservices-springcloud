# microservices-springcloud

### Build artifact
```$ ./gradlew build```

```$ docker-compose build```

If "_layer not found_" error occurred, run ```docker-compose build``` again.

### Run
```$ docker-compose up -d```
### Test script
```$ bash test-em-all.bash```

### Endpoints
App uses self-signed certificates for https, so a browser will tell that connection is insecure.
Authorization: <br>
_username_: **u** <br>
_password_: **p**
#### Zipkin - distributed tracing
http://localhost:9411/zipkin/
#### Eureka - discovery server
https://localhost:8443/eureka/web
#### Swagger - OpenApi documentation
https://localhost:8443/openapi/swagger-ui.html <br>
