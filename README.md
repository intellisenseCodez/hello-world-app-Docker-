# Simple Docker App

A simple helloworld app for docker

A simple nginx helloworld application that helps you learn docker image pulls. Runs a container on port :80

To pull this image:
```
docker pull horlar/hello-world-app:latest
```

To run this image:
```
docker run --name your-app-name -d -p 5000:80 horlar/hello-world-app:latest
```

Visit your browser
```
localhost:5000
```

Dockerhub link: https://hub.docker.com/repository/docker/horlar/hello-world-app/

Github link: https://github.com/intellisenseCodez/hello-world-app-Docker-
