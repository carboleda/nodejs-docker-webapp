# nodejs-docker-webapp
Dockerizing a Node.js web app

https://nodejs.org/en/docs/guides/nodejs-docker-webapp/

### Build docker image:
```
docker build -t carboleda/node-web-app .
```

### Run docker image leaving containr in background
```
docker run -p 49160:8080 -d carboleda/node-web-app
```

### Show container logs:
```
docker ps
docker logs <container id>
```

### Enter the container
```
docker exec -it <container id> /bin/bash
```