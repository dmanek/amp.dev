---
"$title": Подготовка
"$order": '0'
description: Подготовка среды разработки, шаг 1. Скачайте код. Скачайте код примера для данного урока либо в виде ZIP-файла, либо через git...
"$parent": "/documentation/guides-and-tutorials/start/converting/setting-up.md"
---

## Предварительные требования

<strong>Чтобы завершить</strong> этот урок, вам понадобятся:

- Базовые знания HTML, CSS и JavaScript
- Любой браузер, позволяющий просматривать консоль JavaScript
- Текстовый редактор (на ваш выбор)

## Подготовка среды разработки

### Шаг 1. Скачайте код

Скачайте код примера для данного урока либо в виде [ZIP-файла](https://github.com/googlecodelabs/accelerated-mobile-pages-foundations/archive/master.zip), либо через git:

```shell
git clone https://github.com/googlecodelabs/accelerated-mobile-pages-foundations.git
```

Распакуйте файл архива (при необходимости) и перейдите в каталог проекта через командую строку вашего компьютера:

```shell
cd accelerated-mobile-pages-foundations
```

Каталог проекта содержит несколько примеров файлов ресурсов, а также начальную страницу [`article.html`](https://github.com/googlecodelabs/accelerated-mobile-pages-foundations/blob/master/article.html).

### Шаг 2. Запустите страницу-пример

Чтобы протестировать страницу-пример, нужно открыть ее файлы с веб-сервера. Существует несколько способов создать временный локальный веб-сервер для тестирования. Вот несколько вариантов; выберите тот, который вам лучше всего подходит:

- [Приложение «Web Server for Chrome» для Google Chrome](https://chrome.google.com/webstore/detail/web-server-for-chrome/ofhbbkphhbklhfoeikjpcbhemlocgigb)
- [Локальный HTTP-сервер на Python](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/set_up_a_local_testing_server#Running_a_simple_local_HTTP_server)
- [Apache](https://httpd.apache.org/docs/2.4/getting-started.html)
- [nginx](http://nginx.org/)

[tip type="note"] **ПРИМЕЧАНИЕ.**  Для реальных сайтов настоятельно рекомендуем использовать HTTPS. Помимо повышенной безопасности, HTTPS обладает преимуществами в других областях, таких как SEO. Подробнее читайте в [записи в блоге Google Webmaster](https://webmasters.googleblog.com/2014/08/https-as-ranking-signal.html). [/tip]

После создания локального веб-сервера откройте статью-пример в браузере по [этому URL-адресу](http://localhost:8000/article.html):

```text
http://localhost:8000/article.html
```
