## Summary

Docker compose created for Vapor Micro Services architecture
Example how to build docker image for production:

```
docker build -t {your image name}:{your image label} --build-arg env=release -f docker.Dockerfile .
```

### Build docker image for API Gateway

```
docker build -t api-gateway:0.0.1 --build-arg env=release -f docker.Dockerfile .
```

### Build docker image for User Service

```
docker build -t user-service:0.0.1 --build-arg env=release -f docker.Dockerfile .
```
