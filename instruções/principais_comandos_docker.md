# Comandos relevantes para o Docker

* Para visualizar as imagens disponíveis:
```
 sudo docker images
```

* Para listar todos os contêineres Docker em execução: 
```
 sudo docker ps
```

* Para visualizar os logs da execução do container: 
```
 sudo docker logs <nome_conteiner>
```

* Para acessar o terminal interativo dentro do contêiner: 
```
 sudo docker exec -it nome_conteiner /bin/bash
```

* Para ver todas images:

```
sudo docker images 
```

* Para parar todos containers em execução:

```
sudo docker stop $(sudo docker ps -q)
```

* Para remover uma imagem:

```
sudo docker rmi -f <ID> 
```

* Listar todos os contêineres Docker no seu sistema em execução

```
sudo docker ps 
```

* Listar todos os contêineres Docker no seu sistema, incluindo os parados

```
sudo docker ps -a 
```

* Para remover o cotainer

```
sudo sudo docker rm <ID>
```

* Permite que você remova todos os contêineres parados com um único comando.

```
sudo docker container prune   
```

* Isso exibirá os logs de saída do contêiner

```
sudo docker logs <nome_container> 
```

Comando para acessar o terminal interativo dentro do contêiner:

```
docker exec -it nome_contêiner /bin/bash 
```
