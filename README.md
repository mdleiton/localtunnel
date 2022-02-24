# localtunnel

## Описание

Изменил хост стоящий по-дефолту на свой сервер (kobboy.tk), поставил вывод запросов по умолчанию включенным (выкл. --not-print-requests), также внёс небольшие визуальные правки.

## Установка

### Чистая установка

```
(sudo) npm i -g https://github.com/KBDI/localtunnel
```

### Если установлен пакет localtunnel

```
(sudo) npm uninstall -g localtunnel
(sudo) npm i -g https://github.com/KBDI/localtunnel
```

## Пример использования

```
lt -h // Все доступные аргументы
lt -p 80 -s subdomain // Сайт будет доступен по ссылке subdomain.kobboy.tk
```
