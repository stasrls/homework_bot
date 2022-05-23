![](https://img.shields.io/badge/Python-3.7-blue) 
![](https://img.shields.io/badge/SQLite3-green)
![](https://img.shields.io/badge/DjangoRestFramework-3.12.4-red)
![](https://img.shields.io/badge/SimpleJWT-yellow)
![](https://img.shields.io/badge/pythontelegrambot-13.7-blue)

# HomeworkBot

## Описание
Телеграм ЧатБот для проверки статуса домашней работы в Яндекс.Практикуме.

## Запуск проекта в dev-режиме
- Склонируйте этот репозиторий
- Установите и активируйте виртуальное окружение
- Установите зависимости из файла requirements.txt
```
python3 -m pip install --upgrade pip
pip install -r requirements.txt
```

Записать в переменные окружения (файл .env) необходимые ключи:
- Токен профиля на Яндекс.Практикуме
- Токен телеграм-бота(BotFather)
- Ваш ID в телеграме

Выполнить миграции:

```
python3 manage.py migrate
```

Запустить проект:

```
python3 manage.py runserver
```

## Авторы
[Шалгынов Станислав](https://github.com/stasrls)

## Лицензия
The Unlicense
