# README

## Setup

- Up and access container

```shell script
docker-compose up -d
docker exec -it soccer-web bash
```

- <strong>At container</strong> Install depencies

```shell script
bundle instal
yarn install --check-files
```

- Create database and run migrations
```shell script
rails db:create
rails db:migrate
```

## How to run


```shell script
docker-compose up -d
docker exec -it soccer-web rails s -b 0
```