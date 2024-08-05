# Django Skeleton Based Project

## Setup
1. Clone the repository
2. Create a virtual environment and activate it
```bash
python3 -m venv .venv
source .venv/bin/activate
```
3. Install the requirements
```bash
pip install -r requirements.txt
```
4. Make migrations and migrate
```bash
python manage.py makemigrations --no-header
python manage.py migrate
```
5. Create a superuser
```bash
python manage.py createsuperuser
```
6. Run the server
```bash
python manage.py runserver
```

## Addons
### Create a new app

```bash
mkdir apps/<app_name>
python manage.py startapp <app_name> apps/<app_name>
```
