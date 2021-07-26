# API de Vendas
Construindo uma API Restful de Vendas Javascript com Node.js, Express, Typescript, TypeORM, Postgres, Redis, Docker etc.

## Instalar dependências

```
yarn
```

Após a instalação execute a aplicação com o comando `yarn dev`.\
O servidor estará em execução no endereço http://localhost:3333.


## Comando para criar o postgres em docker
```
docker run --name postgres -e POSTGRES_PASSWORD=docker -p 5432:5432 -d postgres
```
