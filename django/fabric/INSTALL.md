Установка системы производится обычным образом для локального окружения.

Создается виртуальное окружение:

```python3 -m venv ~/bin/env```

Переход в виртуальное окружение:

```source ~/bin/env/bin/activate```

Скопировать проект fabric из репозитория в окружение.

Установить пакеты:

```pip install django```
```pip install djangorestframework```

Используемая БД sqlite заполнена, при необходимости выполнить миграцию:

```python manage.py makemigrations poll```
```python manage.py migrate```

Запустить сервер:

```python manage.py runserver```

URL REST клиента:

```http://localhost:8000```

URL панели администратора:

```http://localhost:8000/admin/```

Логин/пароль администратора
admin/admin
