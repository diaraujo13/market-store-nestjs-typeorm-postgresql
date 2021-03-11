## Descrição

<h1> NestJS + TypeORM = :rocket:</h1>
Projeto de uma aplicação full-stack com [Nest](https://github.com/nestjs/nest), Typescript, GraphQL, TypeORM e PostgreSQL.

O NestJS, assim como o TypeORM, faz forte uso dos Decorators do TypeScript, resultando em um código mais limpo e uma arquitetura de software mais consolidade.

Faz-se uso de Docker para conteinerização das aplicações (e facilitar seu futuro deploy), onde temos três contêineres:

- nestjs-server, rodando na porta 3000
- db_server, onde estará nosso servidor PostgreSQL, rodando na porta padrão
- pgadmin, um cliente de interface para o banco, rodando na porta 9000

## Instale as deps

```bash
$ npm install
```

## Execução em ambiente de desenvolvimento

```bash
# development
$ npm run start

# watch mode
$ npm run start:dev

# production mode
$ npm run start:prod
```

## Testes

```bash
# unit tests
$ npm run test

# e2e tests
$ npm run test:e2e

# test coverage
$ npm run test:cov
```

## License

[MIT licensed](LICENSE).
