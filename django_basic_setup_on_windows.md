
Search for python path
C:\Python34\python.exe

Open command prompt and go to director where you want to start project,
```cd C:\sgaikwad\workspace\django-user-profile```


Start virtual env with project's name
```mkvirtualenv django-user-profile -p C:\Python34\python.exe```
Here python exe path is the same we found in step 1


Start virtual env mode
```workon django-user-profile```


Check pip and python versions
 ```pip --version```
 output
 pip 9.0.1 from c:\users\sgaikwad3\envs\django-user-profile\lib\site-packages (python 3.4)

 ```python --version```
 output
 Python 3.4.4


Environment is set, We are ready to go

Install django
```pip install django```


Start django project
```django-admin startproject django_user_profile```

Run the project
```cd django_user_profile\```
```python manage.py  runserver```

Hit URl in browser
```http://localhost:8000/```

Django basic setup is done!


