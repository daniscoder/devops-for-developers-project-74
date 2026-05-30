### Hexlet tests and linter status:
[![Actions Status](https://github.com/daniscoder/devops-for-developers-project-74/actions/workflows/hexlet-check.yml/badge.svg)](https://github.com/daniscoder/devops-for-developers-project-74/actions)

### GitHub CI/CD status:
[![CI](https://github.com/daniscoder/devops-for-developers-project-74/actions/workflows/push.yml/badge.svg)](https://github.com/daniscoder/devops-for-developers-project-74/actions/workflows/push.yml)

# Devops For Developers Project

Учебный проект Hexlet: контейнеризация Node.js-приложения, запуск тестов в Docker Compose и автоматизация через GitHub Actions.

Docker Hub образ: [daniscoder/devops-for-developers-project-74](https://hub.docker.com/r/daniscoder/devops-for-developers-project-74)

## Требования

* Docker
* Docker Compose
* GNU Make

## Быстрый старт

```bash
cp .env.example .env
make setup
make dev
```

Приложение будет доступно на http://localhost

## Полезные команды

```bash
make setup   # установка зависимостей
make dev     # запуск в режиме разработки
make test    # запуск тестов
make ci      # запуск CI локально
make build   # сборка production образа
make push    # публикация образа на Docker Hub
```
