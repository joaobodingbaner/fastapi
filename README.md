# fastapi
repo for learn fastapi

Update:
Create docker image to run fastapi with a postgres database

## install virtualenv
```python
python -m venv fastapi
>fastapi\Scripts\activate
pip install -r requirements.txt
```

## debug local app

```shell
uvicorn main:app --reload
```

http://127.0.0.1:8000/items/

http://127.0.0.1:8000/docs

http://127.0.0.1:8000/redoc


## Docker

### pre requisite

- Docker compose

```shell
docker-compose build
```

```shell
docker-compose up -d
```

http://127.0.0.1:8008/docs

http://127.0.0.1:8008/

Check postgres db

docker-compose exec db psql --username=jb_fastapi --dbname=jb_fastapi

docker volume inspect fastapi_postgres_data


## Docker

### Install

Windows:
https://docs.docker.com/desktop/install/windows-install/


## FastApi Crude

https://testdriven.io/blog/fastapi-crud/

```
mkdir fastapi-crud &&
    cd fastapi-crud &&
    type nul > docker-compose.yml &&
    mkdir src &&
    cd src &&
    type nul > Dockerfile &&
    type nul > requirements.txt &&
    mkdir app &&
    cd app &&
    type nul > __init__.py &&
    type nul > main.py
```

