# Project setup

- Create new virtual environment
- Activate the virtual environment
- Install the requirements ```pip install -r requirements.txt```
- Create credentials.py file in organizational_structure folder. Next to the settings.py file and add the following in it:
```
ENVIRONMENT = 'local'
```
- Apply migrations ```python manage.py migrate```
- Create admin user ```python manage.py createsuperuser```
- Run server ```python manage.py runserver```

