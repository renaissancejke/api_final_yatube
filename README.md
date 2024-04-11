# Цель проекта - создать API для соц. сети Yatube.

## Запуск проекта: 

```bash
python3 -m venv venv
source venv/bin/activate
python3 -m pip install --upgrade pip
pip install -r requirements.txt
python3 manage.py migrate
python3 manage.py runserver
```