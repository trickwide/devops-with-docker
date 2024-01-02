# How to run the application from Docker Hub image

[Link to Docker Hub page](https://hub.docker.com/repository/docker/vilsaast/react-counter/general)

Pull image from Docker Hub

```
docker pull vilsaast/react-counter:latest
```

Run the downloaded Docker Image

```
docker run --name react-counter -p 3000:3000 -d vilsaast/react-counter:latest
```

Open http://localhost:3000/ on your web browser to access the application
