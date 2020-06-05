<h1 align="center">
  <img alt="Logo" src="./readme_assets/logo.svg" width="200px">
</h1>

<h3 align="center">
  GoBarber - BackEnd API
</h3>

<p align="center">Api de agendamento de serviço!</p>

<p align="center">

<p align="center" vertical-align="center">
  <img src="./readme_assets/NODEjs.png?color=%23FF9000" title="Node.js"/>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <img src="./readme_assets/TYPESCRIPT.png" title="Typescript"/>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <img src="./readme_assets/DOCKER.png" title="Docker"/>
</p>



<p align="center">
  <a href="#-sobre-o-projeto">Sobre o projeto API</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-inicio">Começando
</a>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</p>


## 💇🏻‍♂️ Sobre o projeto API

Essa API é para agendamento de serviço de barbearia.

Os clientes podem escolher o melhor horário disponível.

Os barbeiros podem verificar todos os agendamentos disponiveis.

## 🚀 Tecnologias

Tecnologias usada para desenvolver essa API

- [Node.js](https://nodejs.org/en/)
- [TypeScript](https://www.typescriptlang.org/)
- [Express](https://expressjs.com/pt-br/)
- [Multer](https://github.com/expressjs/multer)
- [TypeORM](https://typeorm.io/#/)
- [JWT-token](https://jwt.io/)
- [uuid v4](https://github.com/thenativeweb/uuidv4/)
- [PostgreSQL](https://www.postgresql.org/)
- [Date-fns](https://date-fns.org/)
- [Jest](https://jestjs.io/)
- [SuperTest](https://github.com/visionmedia/supertest)
- [Husky](https://github.com/typicode/husky)
- [Commitlint](https://github.com/conventional-changelog/commitlint)
- [Commitizen](https://github.com/commitizen/cz-cli)
- [Eslint](https://eslint.org/)
- [Prettier](https://prettier.io/)
- [EditorConfig](https://editorconfig.org/)

### Dependência

- [Node.js](https://nodejs.org/en/)
- [Yarn](https://classic.yarnpkg.com/)
- [PostgreSQL](https://www.postgresql.org/)
- [Redis](https://redis.io/)
- [MogoDB](https://www.mongodb.com/)


## 💻 Começando

```bash
# Instalando as Dependencias
$ yarn

# Executando banco de dados postgreSQL no docker
$ docker run --name gobarber-postgres -e POSTGRES_USER=docker \
              -e POSTGRES_DB=gobarber -e POSTGRES_PASSWORD=docker \
              -p 5432:5432 -d postgres

# Executando banco de dados MongoDB no docker
$ docker run --name gobarber-mongodb -p 27017:27017 -d -t mongo

# Executando cache redis
$ docker run --name gobarber-redis -p 6379:6379 -d -t redis:alpine

# Edite o arquivo ".env" com as configurações de ambiente
$ .env

# Edite o arquivo "ormconfig.json" com as configurações de banco de dados
$ ormconfig.json

# executando migrations para criação do banco de dados
$ yarn typeorm migration:run

# Executando o projeto porta 3333
$ yarn dev:server

# Executando teste unitarios
$ yarn test

# Executando unico teste
$ yarn test src/modules/users/services/ResetPasswordService.spec.ts
```


---

by Marlon Barreto 👋 [Linkedin](https://www.linkedin.com/in/marlon-nery-37411479/)
