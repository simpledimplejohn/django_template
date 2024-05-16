# Django Template app
This app has all the inital steps for setting up a django file already done

## Use this reposiotry
1. Clone the repository
2. add a .env file
    This will contain
    ```
    SECRET_KEY=
    API_KEY=
    LOG_LEVEL=debug
    ```
3. add a .gitignore file
4. run
    `python3 manage.py runserver 8000`

## Build this repository
1. create readme.md
2. create .gitignore
3. create .env
4. `django-admin startproject main_project .`
5. `python3 manage.py startapp sub_app`
6. add app to main_project/settings.py INSTALLED_APPS
7. add to main_project/urls.py 
8. Handle keys with decouple
    1. `pip install python-decouple`
    2. settings.py use config('name') to get the key from the .env file
        - remove any keys
9. Start Github
    1. `git init`