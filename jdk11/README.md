# jdk11

Imagem que serve de base para execução de aplicação em Java. Esta imagem é montada conforme a generosa explanação disponível [aqui](https://qiita.com/h-r-k-matsumoto/items/1725fc587ce127671560).

## Docker hub

- https://hub.docker.com/r/kyriosdata/jdk11/ 

# Como criar

- `docker build -t jdk11 .`
- `docker tag IMAGE-ID kyriosdata/jdk11:latest`
- `docker login`
- `docker push kyriosdata/jdk11`