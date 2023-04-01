# RunDevCMS

# 💪 Features

- Code quality check
- Backward compatible with Django

# 🚀 Getting Started

```bash
cookiecutter https://github.com/garpixcms/garpixcms-empty-template
cd {{ project_name }}
python3 -m venv env 
source env/bin/activate
pip install -r requirements.txt
python3 manage.py makemigrations
python3 manage.py migrate
python3 manage.py runserver
```
