```
virtualenv .venv
source .venv/bin/activate
pip install -r requirements.txt
coverage run --source="." manage.py test
coverage report
```
