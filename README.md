# Docker setup

### Prerequisites

- Install [Docker](https://www.docker.com/)
- Install [Docker Compose](https://docs.docker.com/compose/install/)
- Refer docker setup for rails here(https://docs.docker.com/samples/rails/)

## docker commands:

1. Docker compose down -v

## build all the container at a time

2. docker compose up -d --build

## Create a database
3. docker compose run web rake db:create

## Scaffold rails
4. docker compose run web rails g scaffold post title:string comment:string

## Migragte schema to db
5. docker compose run web rails db:migrate

## check db on console
5. docker compose run web rails c
