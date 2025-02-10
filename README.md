![separe](https://github.com/studoo-app/.github/blob/main/profile/studoo-banner-logo.png)
# CYBER TP5 - SQL Injection

Ce repository vise à fournir un exemple d'application non sécurisée face aux injections sql
afin d'appréhender:
- Les ravages potentiels de ce type d'attaque
- Les techniques à mettre en oeuvre afin de protéger son application

## Stack

- PHP
- MariaDb
- Docker
- Docker-compose
- PhpMyAdmin
- Franken

## Installation

- `docker-compose up -d`
- `docker-compose exec app mv .env.example .env`
- `docker-compose exec app composer install`

## Accès

- [http://localhost:8001](http://localhost:8001)
- [http://localhost:8081](http://localhost:8081)