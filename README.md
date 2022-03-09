## NextJS Docker environment

* 1- Crie uma pasta chamada `next-app` e na raiz desta, coloque seu projeto **NextJS**

* 2- Conforme seu ambiente (dev ou prod), renomeie os arquivos adequados para tal
    > ### Se **Dev**:
    > 1. Renomeie o arquivo `Dockerfile.dev` para `Dockerfile`
    > 2. Renomeie o arquivo `docker-compose.yml.dev` para `docker-compose.yml`
    >
    > ----
    >
    > ### Se **Prod**:
    > 1. Renomeie o arquivo `Dockerfile.prod` para `Dockerfile`
    > 2.  Renomeie o arquivo `docker-compose.yml.prod` para `docker-compose.yml`

* 3- Execute o comando `docker-compose up`


----

## TODO

- Receber parâmetros por arquivo `.env` (porta, etc)
