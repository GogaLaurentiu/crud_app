# crud_app
ADV data Base
Install python and PostgreSQL database

https://www.python.org/downloads/

https://www.postgresql.org/download/

Setup Virtual Environments

python3 -m venv django_env
django_env\Scripts\activate.bat
Clone this repository

git clone https://github.com/GogaLaurentiu/Countries-in-the-world-by-Population.git

Enter on project root and install dependency

cd django_crud_app
pip install -r requirements.txt
Setup PostgreSQL database config from .env

DB_NAME=
DB_USER=
DB_PASSWORD=
DB_HOST=
DB_PORT=
Migrate database

python manage.py makemigrations
python manage.py migrate
Run project

python manage.py runserver
