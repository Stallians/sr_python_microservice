# Python Microservices Application

This is a basic FastAPI application now that has a `Hello World` message at its root.  

## Setup  

Install all the libraries mentioned in `requirements.txt` into target virtual environment.

## Steps to run this application  

Execute below line to run the application:

```shell
uvicorn app:app --reload
```

Now, visit the URL - [http://127.0.0.1:8000/](http://127.0.0.1:8000/)

You should see below message:  

```shell
{"message": "Hello World"}
```
