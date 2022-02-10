## Valentin Shorin - REST API on  Flask and SQLAlchemy project
___
### About


### Technologies
- Python 3.10
- Flask 2.0.2
- Flask-marshmallow 0.14.0
- Flask-RESTful 0.3.9
- Flask-SQLAlchemy 2.5.1
___
### Installation
###### Clone repository
```
git clone https://github.com/vshorin-git/REST-API-on-Flask-and-SQLAlchemy.git && cd REST-API-on-Flask-and-SQLAlchemy
```
###### Install virtual environment
```
python3 -m venv venv
source venv/bin/activate
```
###### Install python requirement modules
```
pip install -r requirements.txt
```
###### Initialize database for the project
```
python
from main import db
db.create_all()
exit()
```
##### Run project
```
python3 main.py
```