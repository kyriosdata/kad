# dev

Ambiente para desenvolvimento em Java composto de JDK 11, Maven 3.6.0 e
Git. 

## Docker hub

- https://hub.docker.com/r/kyriosdata/dev/ 

## Como executar

- `docker run -it -v /tmp/dir:/home kyriosdata/dev`<br>
Abre _shell_ na qual estão disponíveis ferramentas de desenvolvimento.
Observe que o diretório **/tmp/dir** na máquina que hospeda o
contêiner estará registrando o que for depositado  no diretório
**home** do contêiner.

# Como criar

- `docker build -t dev .`
- `docker tag IMAGE-ID kyriosdata/dev:latest`
- `docker login`
- `docker push kyriosdata/dev`
