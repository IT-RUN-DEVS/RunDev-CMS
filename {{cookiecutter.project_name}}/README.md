1. Install dependencies:

```
python3 -m venv env
source env/bin/activate
pip install -r requirements.txt
```

2.  migrate database and create super user

```
python3 manage.py makemigrations
python3 manage.py migrate
python3 manage.py createsuperuser
```

3. Run the server:

```
python3 manage.py runserver
```
