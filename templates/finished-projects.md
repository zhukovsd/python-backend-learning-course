+++
title = 'Завершенные проекты'
weight = 30
+++

# Реализации проектов студентами

Список реализаций проектов курса (и не только). Для каждого проекта указана ссылка на код, язык программирования/фреймворк, и ссылка на ревью.

{{ projects | project_count }} реализаций, {{ projects | review_count }} ревью.

[Полная версия таблицы с реализациями проектов](https://zhukovsd.github.io/java-backend-learning-course/finished-projects) на всех языках программирования, не только Python.

Присылайте ваши реализации в чат сообщества - [@zhukovsd_it_chat](https://t.me/zhukovsd_it_chat).

## Виселица

[ТЗ проекта](./projects/hangman.md)

| Репозиторий | Автор | Язык | Ревью | Автор ревью |
|-------------|-------|------|-------|-------------|
{% for p in projects if p.project_name == 'hangman' -%}
| {{ p | repo }} | {{ p | author }} | {{ p | language }} | {{ p | review }} | {{ p | review_author }} |
{% endfor %}

## Симуляция

[ТЗ проекта](./projects/simulation.md)

| Репозиторий | Автор | Язык | Ревью | Автор ревью |
|-------------|-------|------|-------|-------------|
{% for p in projects if p.project_name == 'simulation' -%}
| {{ p | repo }} | {{ p | author }} | {{ p | language }} | {{ p | review }} | {{ p | review_author }} |
{% endfor %}

## Обмен валют

[ТЗ проекта](./projects/currency-exchange.md)

| Репозиторий | Автор | Язык | Ревью | Автор ревью |
|-------------|-------|------|-------|-------------|
{% for p in projects if p.project_name == 'currency-exchange' -%}
| {{ p | repo }} | {{ p | author }} | {{ p | language }} | {{ p | review }} | {{ p | review_author }} |
{% endfor %}

## Теннисное табло

[ТЗ проекта](./projects/tennis-scoreboard.md)

| Репозиторий | Автор | Язык | Ревью | Автор ревью |
|-------------|-------|------|-------|-------------|
{% for p in projects if p.project_name == 'tennis-scoreboard' -%}
| {{ p | repo }} | {{ p | author }} | {{ p | language }} | {{ p | review }} | {{ p | review_author }} |
{% endfor %}

## Погода

[ТЗ проекта](./projects/weather-viewer.md)

| Репозиторий | Автор | Язык | Ревью | Автор ревью |
|-------------|-------|------|-------|-------------|
{% for p in projects if p.project_name == 'weather-viewer' -%}
| {{ p | repo }} | {{ p | author }} | {{ p | language }} | {{ p | review }} | {{ p | review_author }} |
{% endfor %}

## Облачное хранилище файлов

[ТЗ проекта](./projects/cloud-file-storage.md)

| Репозиторий | Автор | Язык | Ревью | Автор ревью |
|-------------|-------|------|-------|-------------|
{% for p in projects if p.project_name == 'cloud-file-storage' -%}
| {{ p | repo }} | {{ p | author }} | {{ p | language }} | {{ p | review }} | {{ p | review_author }} |
{% endfor %}

## Планировщик задач

[ТЗ проекта](./projects/task-tracker.md)

| Репозиторий | Автор | Язык | Ревью | Автор ревью |
|-------------|-------|------|-------|-------------|
{% for p in projects if p.project_name == 'task-tracker' -%}
| {{ p | repo }} | {{ p | author }} | {{ p | language }} | {{ p | review }} | {{ p | review_author }} |
{% endfor %}

## Остальное

Проекты вне курса, которые студенты писали по своей инициативе или по моему совету.

| Репозиторий | Автор | Язык | Ревью | Автор ревью |
|-------------|-------|------|-------|-------------|
{% for p in projects if p.project_name == 'other' -%}
| {{ p | repo }} | {{ p | author }} | {{ p | language }} | {{ p | review }} | {{ p | review_author }} |
{% endfor %}
