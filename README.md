# Fast API example for PKG Deploy


RPM builds with:
* Python3
* pipenv
* FastAPI
* uvicorn
* gunicorn
* nginx


_Note: This is just an example. The settings, requirements, layout etc are not using best practices and are not production ready._


## Local setup

```bash
pipenv install
pipenv shell

uvicorn main:app --reload
```
