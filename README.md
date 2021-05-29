```shell
gh repo clone zxctech/zxc-api
```
## Installation

### Setup Virtual Environment

```shell
virtualenv -p python3.7 venv
source venv/bin/activate
```

### Install Dependencies

```shell
pip install -r requirements.txt
```

## Run the application

```shell
uvicorn app.main:app --host 0.0.0.0 --port 8080 --reload
```

### Updating requirements.txt in venv
```shell
pip freeze > requirements.txt
```