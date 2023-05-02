# АВБ-21 Example

## Docker

- [Установка](https://docs.docker.com/desktop/install/windows-install)
- [Документация по созданию Dockerfile](https://docs.docker.com/engine/reference/builder)
- [MySql Image](https://hub.docker.com/_/mysql)
- [Nginx Image](https://hub.docker.com/_/nginx)
- [Python Image](https://hub.docker.com/_/python)

Сборка:

_Перед запуском нужно установить свои значения в docker/.env/environments_

> docker-compose -f ./docker-compose.yaml --env-file ./.env/environments build

Запуск:

> docker-compose -f ./docker-compose.yaml --env-file ./.env/environments up

## OpenApi

- [Визуализация](https://editor.swagger.io)
