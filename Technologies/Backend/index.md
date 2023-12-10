# Backend

Этот документ посвящён необходимым знаниям, относящихся к Python Backend, напрямую или косвенно.

## Общие знания

Владение общими знаниями хорошо тем, что они применимы к любой Backend платформе, будь то Java, .Net, NodeJS или другие.

### Клиент-серверное взаимодействие, IP адреса, DNS

Базовые идеи, о которых необходимо иметь общее представление. Что нужно знать:
- Что такое IP адрес
- Разница между TCP и UDP
- Что такое TCP сокет
- Клиент-серверное взаимодействие. Что именно происходит, когда браузер запрашивает страницу сайта
- Что такое DNS

#### Избранные курсы и учебные ресурсы

- [Плейлист](https://www.youtube.com/playlist?list=PLnh8EajVFTl7_p5MgevvA41PvxQWq-jC8) от dmdev - уроки с 1 по 6
- [https://developer.mozilla.org/ru/docs/Learn/Common_questions/How_does_the_Internet_work](https://developer.mozilla.org/ru/docs/Learn/Common_questions/How_does_the_Internet_work)
- [https://developer.mozilla.org/ru/docs/Learn/Getting_started_with_the_web/How_the_Web_works](https://developer.mozilla.org/ru/docs/Learn/Getting_started_with_the_web/How_the_Web_works)

### HTTP

Главный протокол WEB.

Что нужно знать:
- HTTP методы
- Заголовки, cookies
- Коды ответа
- Form data, multipart form data

#### Избранные курсы и учебные ресурсы

- [Статья](https://zametkinapolyah.ru/servera-i-protokoly/chto-nuzhno-znat-pro-http-protokol-veb-razrabotchiku-pravila-http-protokola.html) про HTTP простым языком
- Практика - проекты, начиная с 3

## REST API

REST - набор правил взаимодействия клиента и сервера на основе HTTP. Сделать работающее клиент-серверное приложение легко, элегантно его спроектировать - сложно. 

Что нужно знать:
- Отличие RESTful от RESTless
- Базовые дизайн принципы и типовые ошибки, которых следует избегать

#### Избранные курсы и учебные ресурсы

- Статьи по REST на хабре - [#1](https://habr.com/ru/post/483202/), [#2](https://habr.com/ru/post/351890/)
- Книга по дизайну REST API - [https://www.amazon.com/REST-Design-Rulebook-Mark-Masse/dp/1449310508](https://www.amazon.com/REST-Design-Rulebook-Mark-Masse/dp/1449310508)
- Практика - проекты #3 ["Обмен валют"](../../Projects/CurrencyExchange/index.md) и #7 ["Планировщик задач"](../../Projects/TaskTracker/index.md) содержат примеры дизайна REST API

## Python

Перейдём к знаниям, относящимся напрямую к Backend разработке на Python.

### Разработка бэкенд приложений без фреймворков

Что нужно уметь:
- Пользоваться библиотекой http.server и технологией uWSGI для реализации бэкенд приложений 

#### Избранные курсы и учебные ресурсы

- TODO
- Практика - проекты 3, 4

### Django

Django - один из основных фреймворков для веб разработки на Python.

Что нужно уметь:
- Работать с базами данных
- Реализовывать REST API
- Создавать веб страницы
- Библиотеки экосистемы Django - Django ORM, и другие

#### Избранные курсы и учебные ресурсы

- Курс [Добрый, добрый Django](https://stepik.org/course/183363/) от Сергея Балакирева
- [Плейлист](https://www.youtube.com/playlist?list=PLA0M1Bcd0w8yU5h2vwZ4LO7h1xt8COUXl) из 70 уроков от Сергея Балакирева
- Качественная [официальная документация](https://docs.djangoproject.com/en/5.0/)
- Практика - проекты 5, 6

## FastAPI

TODO

### Шаблонизаторы веб-страниц

Шаблонизатор - инструмент создания веб-страниц с динамическим контентом. Классический пример - отображение на веб-странице информации, прочитанной из базы данных.

Для Python существует множество шаблонизаторов. Остановимся на Jinja2.

Что нужно уметь:
- Передавать данные из Python в шаблон
- Использование Jinja2 в проекте с фреймворком и без него

#### Избранные курсы и учебные ресурсы

- [Плейлист](https://www.youtube.com/playlist?list=PLA0M1Bcd0w8wfmtElObQrBbZjY6XeA06U) по Jinja2 от selfedu
- [Руководство по шаблонам](https://proglib-io.turbopages.org/turbo/proglib.io/s/p/rukovodstvo-dlya-nachinayushchih-po-shablonam-jinja-v-flask-2022-09-05)
- Практика - проекты 5, 6

## Что дальше

Перечисленные выше знания и инструменты - база для Junior. Если есть желание и необходимость углубиться в Backend технологии, советую обратить внимание на:
- Websocket
- XML, Protobuf
- Альтернативны REST - SOAP, GRPC, GraphQL
- Другие Python фреймворки, например Flask
- Написание бэкенд приложений в реактивном стиле
