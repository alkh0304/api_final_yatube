# Yatube

## Описание

Социальная сеть на Django (frontend и backend) для ведения дневников с возможностью у пользователей создавать учетные записи, публиковать посты, подписываться на авторов, отмечать понравившиеся записи и комментировать посты.

Реализовано взаимодействие с проектом через API и аутентификация по JWT токену.

## Технологии и библиотеки:
- [Python](https://www.python.org/);
- [Django](https://www.djangoproject.com);
- [Pillow](https://pillow.readthedocs.io/en/stable/);
- [SQLite3](https://www.sqlite.org/index.html);
- [Simple-JWT](https://django-rest-framework-simplejwt.readthedocs.io/en/latest/);
- [Django REST Framework](https://www.django-rest-framework.org).

### Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/alkh0304/api_final_yatube.git
```

```
cd api_final_yatube
```

Cоздать и активировать виртуальное окружение:

```
python -m venv venv
```

```
source venv/bin/activate
```

```
python -m pip install --upgrade pip
```

Установить зависимости из файла requirements.txt:

```
pip install -r requirements.txt
```

Выполнить миграции:

```
cd yatube_api
```

```
python manage.py migrate
```

Запустить проект:

```
python manage.py runserver
```

Примеры запросов к API:

```
GET, POST api/v1/posts/
```

```
GET, PUT, PATCH, DELETE api/v1/posts/{id}/
```

```
GET, POST api/v1/posts/{post_id}/comments/
```

```
GET, PUT, PATCH, DELETE api/v1/posts/{post_id}/comments/{id}/
```

```
GET api/v1/groups/
```

```
GET api/v1/groups/{id}/
```

```
GET, POST api/v1/follow/
```

```
POST api/v1/jwt/create/
```

```
POST api/v1/jwt/refresh/
```

```
POST api/v1/jwt/verify/
```

## Над проектом Yatube работал:

[Александр Хоменко](https://github.com/alkh0304)