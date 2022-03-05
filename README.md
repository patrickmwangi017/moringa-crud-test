# A Blog Website to show CRUD Operations using Django

## Step 1.1 Create a settings.ini
create a settings.ini file in kernel directory add the following
```ini
[settings]
DEBUG=True
SECRET_KEY=SOMEKEY
```
## Step 1.2 Django configuration
installing dependencies and migrating database
```commandline
pip install -r requirements.txt
python manage.py makemigrations
python manage.py migrate
```

## Step 1.3 For running tests
```commandline
python manage.py test
```

## Step 1.4 Running Server
```commandline
python manage.py runserver
```