# GoBarber_Backend
Backend da aplicação GoBarber, apresentado pelos ensinamentos da [Rocketseat](https://rocketseat.com.br/). 

Para o funcionamento da aplicação é necessário rodar um:

```
yarn install
``` 

para baixar as dependências do projeto.

Depois é necessário configurar os o Mongo, Postgres e o Redis e seguir o env.example para que o database funcione de forma apropriada.

Foi utilizado o docker e os comandos para criação de cada banco foi:

```
docker run --name <nome> -e POSTGRES_PASSWORD=<senha> -p 5432:5432 -d postgres
docker run --name <nome> -p 27017:27017 -d -t mongo
docker run --name <nome> -p 6379:6379 -d -t redis:alpine
```

e no caso do teste do email, foi usado o [mailtrap](https://mailtrap.io/).

Para o melhor funcionamento e visualização é recomendado baixar o Frontend e Mobile para tirar melhor proveito.
