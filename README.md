**Как запустить проект:**
Клонировать репозиторий и перейти в него в командной строке:
```
git clone git@github.com:Pavel2Polishchuk/api_final_yatube.git
```
```
cd kittygram
```

Cоздать и активировать виртуальное окружение:

```
python -m venv env
source env/bin/activate
```
Установить зависимости из файла requirements.txt:

```
python -m pip install --upgrade pip
pip install -r requirements.txt
```

Выполнить миграции:

```
python manage.py migrate
```
Запустить проект:

```
python3 manage.py runserver
```