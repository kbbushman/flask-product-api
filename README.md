# Flask API
Minimal API built with Flask, SQLAlchemy, And Marshmallow.

## Steps

#### Download or Pull This Repo
Click on the green "Clone or download" above.

#### Install Dependencies
Once downloaded, open the project directory in your terminal and run:
```
pip3 install -r requirements.txt
```

#### Create SQLite Databse
In terminal, open a Python shell:
```
python3
```
Import database schema:
```
from app import db
```
Create the database from schema:
```
db.create_all()
```
Quite Python shell:
```
quit()
```

#### Start Flask Server
From the project directory in your terminal, run:
```
python3 app.py
```
