# Cinema Service API
API service for management movies in cinema.
# Installation
For installation run this commands in terminal
```
git clone https://github.com/AVyha/cinema_API.git
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
set DB_HOST=<your db hostname>
set DB_NAME=<your db name>
set DB_USER=<your db username>
set DB_PASSWORD=<your db user password>
set SECRET_KEY=<your secret key>
python manage.py migrate
```

For starting django project use `python manage.py runserver 7000`

# Docker
Run this commands in terminal 
```
docker-compose build
docker-compose up
```
Default domain: `127.0.0.1:7000`

# Features
- functional for managing cinema service
- image storage
- JSON token
- PostgreSQL database

You can see all functional in documentation `<domain>/api/doc/swagger/`



