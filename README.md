# Социальная сеть, позволяет создавать блоги

## Описание:
Социальная сеть, которая позволяет пользователям делится записями, заходить на
чужие страницы, подписываться на других пользователей и комментировать их записи.
Также пользователи могут создавать сообщества по интересам и выкладывать записи в них.

## О проекте
В проекте использован следующий стек:
- Python 3.7
- Django 2.2

## Установка и запуск проекта:
1. Клонировать репозиторий и перейти в него в командной строке:
```
git clone https://github.com/Alexander-Fedorovtsev/hw05_final-master.git
```
cd yatube
```

2. Cоздать и активировать виртуальное окружение (для Windows):
```
python -m venv venv
```
```
source venv/Scripts/activate
```

3. Обновить pip в виртуальном окружении (для Windows):
```
python -m pip install --upgrade pip
```

4. Установить зависимости из файла requirements.txt:
```
pip install -r requirements.txt
```

5. Перейти в папку проекта:
```
cd yatube
```

6. Выполнить миграции:
```
python manage.py migrate
```

7. Создать суперпользователя:
```
python manage.py createsuperuser
```

8. Запустить проект:
```
python manage.py runserver
```

Войти в админку: http://127.0.0.1:8000/admin