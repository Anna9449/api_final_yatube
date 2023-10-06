# api_final
### Описание:

Yatube API - это учебный проект социальной сети, которая дает возможность:
- просматривать публикации других авторов и выкладывать свои
- комментировать публикации
- подписываться на других авторов

### Технологии:

- Python
- Django
- DRF
- JWT + djoser

### Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/Anna9449/api_final_yatube.git
```

```
cd yatube_api
```

Cоздать и активировать виртуальное окружение:

```
python3 -m venv env
```

* Если у вас Linux/macOS

    ```
    source env/bin/activate
    ```

* Если у вас windows

    ```
    source env/scripts/activate
    ```

```
python3 -m pip install --upgrade pip
```

Установить зависимости из файла requirements.txt:

```
pip install -r requirements.txt
```

Выполнить миграции:

```
python3 manage.py migrate
```

Запустить проект:

```
python3 manage.py runserver
```
### Документация к API:

Документация к API проекта Yatube (v1) доступна по ссылке
http://127.0.0.1:8000/redoc/

### Автор

Анна Пестова
