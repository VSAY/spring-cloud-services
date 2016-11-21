# Build Instructions 

## Maven Build 
```
mvn clean package 
```

## Docker Build 

```
docker build -t eureka-server:latest .
```
Refer Dockerfile for more info 

Note: Pre-build images are available on dockerhub look for *vsay/eureka-server:latest*


## Docker Compose run 

### Start Service 
```
docker-compose up -d 
```

### Logs 
```
docker-compose logs -f 
```

