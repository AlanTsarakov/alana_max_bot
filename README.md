## Алана - Первый Осетинский AI Чат-бот
Ссылка на .env внутри отосланного документа

<div align="center">


**Первый чат-бот для общения на осетинском языке с искусственным интеллектом**

[![Python](https://img.shields.io/badge/Python-3.11-blue.svg)](https://python.org)
[![Docker](https://img.shields.io/badge/Docker-Enabled-green.svg)](https://docker.com)
[![Yandex Cloud AI](https://img.shields.io/badge/Yandex_Cloud_AI-Integrated-orange.svg)](https://cloud.yandex.ru)

</div>

## О проекте

Алана - это инновационный чат-бот, который использует современные технологии искусственного интеллекта для общения на осетинском языке. Проект сочетает в себе традиции осетинской культуры и передовые технологии машинного обучения.

### Особенности

- **Общение на осетинском** - первый AI-бот с поддержкой осетинского языка
- **Yandex GPT Integration** - мощная генерация текстов от Yandex Cloud AI
- **Двуязычный интерфейс** - автоматический перевод между русским и осетинским
- **Docker контейнеризация** - простая установка и запуск
- **Max API** - разработан на базе MAX
- **Уникальное мини-приложение** - изучение языка в игровой форме

##  Быстрый старт

### Скачать Docker образ

 **Готовый образ (56MB):** [Скачать с Google Drive](https://drive.google.com/drive/folders/1YYs3d5DaENeEwX9OtahYXqwDGGDCSKXC?usp=sharing)

### Запуск за 3 шага:
Файл .env находится внутри архива с файлами решения. Также в .docx продублированы ключи.
```bash
# 1. Скачайте alana-max-bot.tar.gz с Google Drive

# 2. Загрузите образ в Docker
docker load < alana-max-bot.tar
или
docker load < alana-max-bot.tar.gz
или
docker load -i alana-max-bot.tar
или
docker load -i alana-max-bot.tar.gz(Windows PowerShell)

# 3. Запустите контейнер
docker run -d --name alana-bot --env-file .env alana-max-bot
