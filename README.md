# My Hacks Docker

Guardei essas anotações e comandos afim de facilitar minha vida da hora de matar contêineres e imagens no Docker.


## Listar todos os contêineres (apenas IDs)

```docker
docker ps -aq
```

## Parar todos os contêineres em execução

```docker
docker stop $(docker ps -aq)
```

## Remover todos os contêineres

```docker
docker rm $(docker ps -aq)
```

## Remover todas as imagens

```docker
docker rmi $(docker images -q)
```

---
