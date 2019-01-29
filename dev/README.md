# dev

Ambiente para desenvolvimento em Java composto de JDK 11, Maven 3.6.0 e
Git. 

## Docker hub

- https://hub.docker.com/r/kyriosdata/dev/ 

# Como criar

- `docker build -t dev .`
- `docker tag IMAGE-ID kyriosdata/dev:latest`
- `docker login`
- `docker push kyriosdata/dev`