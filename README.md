<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo_text.svg" width="320" alt="Nest Logo" /></a>
</p>

## Clone the repo

```bash
$ git clone https://github.com/kajal98/nestjs-graphql-stripe.git

$ cd nestjs-graphql-stripe

$ npm i

$ npm run build
```

## Setup the database in ormconfig.json file

```bash
{
    "type": "postgres",
    "host": "localhost",
    "port": 5432,
    "username": "username",
    "password": "password",
    "database": "nestjs-graphql-stripe",
    "entities": ["dist/**/*.entity{.ts,.js}"],
    "synchronize": true,
    "logging": true
}
```

## Run the app

<strong> $ nest start --watch </strong>

## Description

Run below API in Postman and see the output with all User crwated in your Stripe account also.

<strong> For create users in your database and create customer and their invoice into stripe: </strong>

![stripe](https://user-images.githubusercontent.com/18494848/91725293-2841c780-ebbc-11ea-910c-3e28b0600ca9.png)
