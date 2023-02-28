### "Yamdb"
### Описание проекта:
"api_yamdb" - база отзывов о фильмах, книгах, музыке. Работал в команде, отвечал за создание модели User, регистрацию, аутентификацию.
### Установка:
Клонировать репозиторий и перейти в него в командной строке:
- git clone https://github.com/Itdxl/api_yamdb

Cоздать и активировать виртуальное окружение:
- python3 -m venv venv source venv/bin/activate

Установить зависимости из файла requirements.txt:
- python3 -m pip install --upgrade pip pip install -r requirements.txt

Выполнить миграции:
- python3 manage.py migrate

Запустить проект:
- python3 manage.py runserver

### Стек: Python3, Django, Rest-API, django rest framework

### Системные требования: см. requirements.
