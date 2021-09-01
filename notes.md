# Some notes on learning Flask

Run the Application

```bash
export FLASK_APP=flaskr
export FLASK_ENV=development
flask run
```

Initialize the Database file

```bash
flask init-db
# Initialized the database.
```


Run Coverage

```bash
coverage run --omit 'venv/*' -m pytest
coverage report 
coverage html
```

https://flask.palletsprojects.com/en/2.0.x/tutorial/tests/

tests/test_auth.py
