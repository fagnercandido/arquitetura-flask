# alqi_chatbot Backend

## Environment

Python 3.6+
Ative a sua virtualenv

```bash
pip install -r requirements.txt
pip install -r requirements_dev.txt
pip install -r requirements_test.txt
```

## Testing

```bash
pytest alqi_chatbot/tests
```

## Executing

```bash
flask create-db  # rodar uma vez
flask populate-db # rodar uma vez
flask run
```

Access:

- Website: http://localhost:5000
- API GET:
  - https://localhost:5000/api/v1/product/
  - https://localhost:5000/api/v1/product/1
  - https://localhost:5000/api/v1/product/2
  - https://localhost:5000/api/v1/product/3


## Based code from:
```bash
git clone https://github.com/codeshow/003-arquitetura-flask.git
```
