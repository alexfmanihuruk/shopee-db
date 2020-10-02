# SHOPEE DB

Database container

This repository will be used together with it's related service

## Prerequisites

* [install](https://docs.docker.com/install/) [docker](https://www.docker.com/)


## Running this individually

* `$ cp .env.example .env`
* `$ docker-compose up -d --build`
* `$ docker exec -ti shopee-db sh`

## Restarting

* `$ docker restart shopee-db`

## Hard restart

* `$ docker stop shopee-db && docker rm shopee-db && docker-compose up -d --build`
