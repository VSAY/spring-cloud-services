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


## Docker Compose run 

### Start Service 
```
docker-compose up -d 
```

### Logs 
```
docker-compose logs -f 
```

