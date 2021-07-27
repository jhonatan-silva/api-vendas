# API de Vendas

Construindo uma API Restful de Vendas Javascript com Node.js, Express, Typescript, TypeORM, Postgres, Redis, Docker etc.

## Instalar as dependências

```
yarn
```

## Criar as tabelas

```
yarn typeorm migration:run
```

## Executar a aplicação

```
yarn dev
```

O servidor estará em execução no endereço http://localhost:3333

# Comandos extras

## Criar o postgres no docker

```
docker run --name postgres -e POSTGRES_PASSWORD=docker -p 5432:5432 -d postgres
```

## Criar migration

```
yarn typeorm migration:create -n CreateTableName
```
