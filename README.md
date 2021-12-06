# INSTACLONE
## Author

David Mathaga


## Setup Requirements

* Git
* Github
* Django
* Python
* PostgreSQL

## Getting started 

This project is basic social media clone with features like 
User authentication, 
Image with Description Post, 
Post like, 
Post comment, 
User profile,
User follow/unfollow,
Post search,
User search,
Mobile Responsive,
Post Share

### Prerequisites
Things you need to install the project and how to install them
```
Python : https://www.python.org/
Django : pip install django
```
### Installing and SetUp
1) Clone or download this project.
2) Set Up Virtual Environment and activate it
```
python -m venv --without-pip env
source env/bin/activate
```
3) Install dependencies
```
pip install -r requirements.txt
```
4) Change database settings in case you want to use PostgreSQL or MySQL
5) Migrate data using command 
```
python manage.py makemigrations
python manage.py migrate
```
6) Create Superuser
```
python manage.py createsuperuser
```
7) Run project on localhost:
```
python manage.py runserver
```
