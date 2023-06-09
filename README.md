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

### Install

Windows:
https://docs.docker.com/desktop/install/windows-install/

## Dbeaver

SQL client to run queries

https://dbeaver.io/download/

