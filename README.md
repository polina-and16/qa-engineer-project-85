### Hexlet tests and linter status:
[![Actions Status](https://github.com/polina-and16/qa-engineer-project-85/actions/workflows/hexlet-check.yml/badge.svg)](https://github.com/polina-and16/qa-engineer-project-85/actions)
project: Codebattle

description: >
  Codebattle — это онлайн-игра для программистов, в которой участники соревнуются
  друг с другом в решении алгоритмических задач. В игровом лобби можно выбрать
  соперника и начать матч: оба игрока получают одинаковое задание и должны как
  можно быстрее написать корректное решение. Побеждает тот, кто первым проходит
  все тесты.

features:
  - name: Лобби игроков
    description: список доступных соперников, с которыми можно начать игру
  - name: Матчи на скорость
    description: решение задачи против реального человека или бота
  - name: Рейтинги и лидерборды
    description: таблица лучших игроков недели, месяца и всего времени
  - name: Система уровней
    description: у каждого пользователя отображается рейтинг и прогресс
  - name: Чат
    description: возможность общаться в лобби или во время игры
  - name: История игр
    description: завершённые матчи можно пересматривать

repository_structure:
  - path: app/
    description: серверная часть приложения
  - path: assets/
    description: фронтенд и статические ресурсы
  - path: priv/repo/
    description: миграции базы данных
  - path: test/
    description: тесты для проверки работоспособности
  - path: Makefile
    description: команды для сборки и запуска
  - path: docker-compose.yml
    description: конфигурация для запуска проекта через Docker

local_setup:
  steps:
    - description: Склонируйте репозиторий
      command: git clone https://github.com/hexlet-codebattle/codebattle.git
    - description: Перейдите в папку проекта
      command: cd codebattle
