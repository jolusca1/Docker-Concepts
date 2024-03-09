Init

# Após instalação geral do docker

## Primeiros comandos

"docker run hello-world" -> container é criado porém não há nenhum entrypoint para manter o container vivo, portanto, ele é criado e logo após desligado.

"docker ps" -> retorna os containeres que estão rodando.

docker ps
CONTAINER ID   IMAGE     COMMAND   CREATED   STATUS    PORTS     NAMES

"docker ps -a" -> retorna os containers que estão ativos e os que estão inativos.

docker ps -a
CONTAINER ID   IMAGE         COMMAND    CREATED         STATUS                     PORTS     NAMES
515bc3685400   hello-world   "/hello"   5 minutes ago   Exited (0) 5 minutes ago             funny_bhaskara
