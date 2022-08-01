<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo_text.svg" width="320" alt="Nest Logo" /></a>
</p>

## Description

KT backend is built using [Nest](https://github.com/nestjs/nest) framework.

### Installation

```bash
$ yarn
```

### Running the app

```bash
# development
$ yarn start

# watch mode
$ yarn start:dev

# production mode
$ yarn start:prod
```

### Test

```bash
# unit tests
$ yarn test

# e2e tests
$ yarn test:e2e

# test coverage
$ yarn test:cov
```

### Support

Nest is an MIT-licensed open source project. It can grow thanks to the sponsors and support by the amazing backers. If you'd like to join them, please [read more here](https://docs.nestjs.com/support).

Nest is [MIT licensed](LICENSE).

## Docker and docker-compose

To proceed, be sure Docker is installed and docker-compose command available. More details about Docker installation can be found in [this documentation](https://docs.docker.com/compose/install/)


To run Node.js server and MongoDB in Docker containers, use the next commands:

```bash
# start
$ docker-compose up

```
and navigate to [localhost:8080/api](http://localhost:8080/api) to access th Swagger UI, where all available endpoints can be found.
To play directly with MongoDB, use VS Code extention [MongoDB for VS Code](https://marketplace.visualstudio.com/items?itemName=mongodb.mongodb-vscode). It allows you to connect to MongoDB and Atlas directly from your VS Code environment, navigate your databases and collections, inspect your schema and use playgrounds to prototype queries and aggregations.

To stop the app, use Ctrl + C and the next command:
```bash
# to stop
$ docker-compose down

```


