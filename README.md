# localtunnel

## Описание

Изменил хост стоящий по-дефолту на свой сервер (kobboy.tk), поставил вывод запросов по умолчанию включенным (выкл. --not-print-requests), также внёс небольшие визуальные правки.

## Установка

### Чистая установка

```
(sudo) npm i -g https://github.com/KBDI/localtunnel
или
(sudo) npm i -g KBDI/localtunnel
```

### Если установлен пакет localtunnel, сначала удалите его

```
(sudo) npm uninstall -g localtunnel
(sudo) npm i -g https://github.com/KBDI/localtunnel
или
(sudo) npm i -g KBDI/localtunnel
```

Чтобы скачать репозиторий из гитхаба, должен быть установлен git!

## Пример использования

```
lt -h # Все доступные аргументы
lt -p 80 -s subdomain # Сайт будет доступен по ссылке subdomain.kobboy.tk
```

### Скриншот выполнения
![image](https://user-images.githubusercontent.com/56311174/155519616-15fbb8cc-6e44-4fd4-a23a-19cf06574bb6.png)

