# GigaChat project [in development]
GigaChat project is an open-source free social platform, written in native code for each supported operating system. The idea behind the project is combining the most useful features of all the most popular messangers/social networks (e.g. Discord, Whatsapp, Telegram) while keeping off their disadvantages. While it is highly unlikely someone would be interested in a school project, we welcome any sort of help!

## TODO:
* разработать серверную хэш-функцию 

### ТЕРМИНЫ
* AA - Account Authorization - Авторизация Аккаунта - Сервера этого типа отвечают за внешную обработку токенов, регеистрацию аккаунтов, и генерацию токенов доступа к ним.
* CDN - Content Delevery Network - Сеть Доставки Контекта - Сервера этого типа отвечают за обмен команд и с пользователями, и при необходимости пересылку на CC-сервера.
* NCC - No Central Control - Без Центрального Контроля - Сервера этого типа может скачать и запустить любой человек. Данные сервера целиком и полностью лежат в его зоне ответственности. Могут использовать CDN-сервера для проксирования, если не нарушают правила. Иначе, только прямое подключение от клиента.
* CC  - Central Core - Центральное Ядро - Сервера этого типа хранят локализованные и централизованные данные, отвечают за приём команд от CDN-серверов, и при необходимости, пересылку другим CDN-серверам.
* FT - Files Transmitting - Транспортировка Файлов - Сервера этого типа отвечают за работу с динамическими пользовательскими файлами.
* TTG - Time-Tokens Generator - Генератор Временных Токенов - Сервера этого типа отвечают за генерацию и валидацию временных и ограниченных токенов доступа к внутренним и внешним сервисам аккаунта пользователя.
* RTC - Real-Time Communications - Коммуникация в Реальном Времени - Сервера обработки датаграмм пользователей.

# Repositories
there are two types of repositories currently, repos for server points and for clients. Each server repo has API description in it's readme, and each client has Installation guides
note: while still in development, instructions may be incomplete.

# Our current tasks:
* finish CDN (RTCD repo) server
* make server to request message history
* finishing clients

# Contributing
no information here yet...
