# python-flask-webapp

## Setup

### Installing Virtual Env

```bash
  # install prerequisite for venv
  sudo apt install python3-venv -y

  # install venv
  python3 -m venv .

  # activate venv
  source bin/activate
```

### Installing Dependencies

```bash
  # pip install SQLAlchemy flask flask-jsonpify flask-sqlalchemy flask-restful
  pip install -r requirements.txt

  # to freeze deps
  # pip freeze > requirements.txt
```



### Start server
```bash
  FLASK_APP=src/app.py flask run

  # server can be accessed at http://localhost:5000/
```


## Links
- https://www.codementor.io/sagaragarwal94/building-a-basic-restful-api-in-python-58k02xsiq
