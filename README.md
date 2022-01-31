# microservices-springcloud

./gradlew build

docker-compose build
#if "layer not found" error ocurred, run docker-compose build again.
### Endpoints
App uses self-signed certificates for https, so a browser will tell that connection is insecure.
#Zipkin - distributed tracing
http://localhost:9411/zipkin/
#Eureka - discovery server
http://localhost:9411/eureka/web
