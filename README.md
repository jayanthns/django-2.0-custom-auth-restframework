# django-2.0-custom-auth-restframework

Steps:

1. Create a empty folder with any name. 
2. Get the project (Clone or Download this project)
3. Create virtual env with python3.6 version.
   Command to create virtual environment: 
   cmd: virtualenv env --python=python3.6
4. Activate the environment: 
   cmd: source env/bin/activate
5. Install the requirements.
   cmd: pip install -r requirements.txt
6. In the jaintapp/config.cfg file, add the db credentials (POSTGRESQL)
7. Run the command: 
   python manage.py makemigrations account
8. Next command: 
   python manage.py migrate
9. Next command to create admin/superuser: 
   python manage.py createsuperuser
10. Next command to run the server: 
   python manage.py runserver 0.0.0.0:8000
11. Enjoy..
