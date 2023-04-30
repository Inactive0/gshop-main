# gshop-main
Проект для фреймворка DJANGO E-COMMERCE

## Содержание
- [Технологии](#технологии)
- [Использование](#использование)
- [Требования](#требования)
- [Автор не совсем](#автор-не-совсем)
- [Источники](#источники)

## Технологии
- [Django](https://www.djangoproject.com/)
- [TypeScript](https://www.typescriptlang.org/)
- ...

## Использование
Как установить и использовать этот проект, пример кода:

1. Установите проект с помощью zip или используйте эту команду:
```sh
$ git clone https://github.com/Inactive0/gshop-main.git
```
2. Установить виртуальное окружение с помощью (PyCharm в моем случае) или вручную как в следующем коде:
```sh
py -m venv venv
```

3. После этого в проекте именно в терминале ввести следующий код:
```sh
.\venv\Scripts\activate
```

4. Cледующий шаг установить в проект Django:
```sh
pip install django
```

5. Cледующий шаг установить в проект Pillow:
```sh
python -m pip install Pillow
```

6. Выполнить следующий код для миграций:
```sh
python manage.py makemigrations
```

7. Выполнить миграцию:
```sh
python manage.py migrate
```

8. Для работы с проектом надо создать суперпользователя:
```sh
python manage.py createsuperuser
```

9. Запустить проект:
```sh
python manage.py runserver
```

### Требования
Для установки и запуска проекта, необходим [Django](https://www.djangoproject.com/).

### Зачем вы разработали этот проект?
Чтобы был.

## Автор не совсем
- [Oraz Ersultan](http://t.me/Floyxkag) — Student Front-End Engineer
- [Tolegenov Berik](https://t.me/Tulegenovvvvvv) — Student Front-End Engineer

## Источники
Learn Django by Building an Online Marketplace – Python Tutorial for Beginners - [Ссылка](https://youtu.be/ZxMB6Njs3ck)
