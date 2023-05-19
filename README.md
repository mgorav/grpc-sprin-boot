# Spring Boot gRPC 
Spring Boot gRPC

## Build
```
mvn clean install 

Run Spring boot app: GrpcSpringBootExampleApplication

```
## Run
```
  grpcurl --plaintext localhost:9090 list
  grpcurl --plaintext localhost:9090 list com.gonnect.grpc.GreetingService
  grpcurl --plaintext -d '{"message": "How are you?"}' localhost:9090 com.gonnect.grpc.GreetingService/greeting
  
```

#