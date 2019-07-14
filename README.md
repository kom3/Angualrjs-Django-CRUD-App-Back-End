# Angualrjs-Django-CRUD-App-Back-End

official site for reference : https://www.django-rest-framework.org/tutorial/quickstart/


note: Create serializers.py inside app(api) directory.




<<<<<<<<<<<<<<==============follow these cammands:=============>>>>>>>>>>>>>>>>>>>

# Create the project directory
mkdir tutorial
cd tutorial

# Create a virtual environment to isolate our package dependencies locally
python3 -m venv env
source env/bin/activate  # On Windows use `env\Scripts\activate`

# Install Django and Django REST framework into the virtual environment
pip install django
pip install djangorestframework

# Set up a new project with a single application
django-admin startproject tutorial .  # Note the trailing '.' character
cd tutorial
django-admin startapp quickstart
cd ..
============================================================================================

<<<<<<<<<<<-------------Only things to be modified for any other projects are:---------------->>>>

Inside api
1. models.py
2. serializers.py
3. views.py
4. admin.py

In root directory

1. settings.py
2. urls.py
