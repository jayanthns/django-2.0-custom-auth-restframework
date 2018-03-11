# django-2.0-custom-auth-restframework

Steps:

1. Create a empty folder with any name. 
2. Get the project (Clone or Download this project)
3. Create virtual env with python3.6 version.
   Command to create virtual environment: ```virtualenv env --python=python3.6```
4. Activate the environment: ```source env/bin/activate```
5. In the jaintapp/config.cfg file, add the db credentials (POSTGRESQL)
6. Run the command: ```python manage.py makemirations```
7. Next command: ```python manage.py migrate```
8. Next command: ```python manage.py createsuperuser``` to create admin/superuser
9. Next command: ```python manage.py runserver 0.0.0.0:8000``` to run the server
10. Enjoy..
