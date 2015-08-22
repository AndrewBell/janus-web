## Build Docker Image

    mvn package

## Run Docker Image

    docker run -d -p 8090:8090 janus/janus-web:latest
    
Set environment variable DOCKER_HOST=tcp://hostname:2375 to run against a remote Docker host. Otherwise, will use localhost